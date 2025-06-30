# Monitoramento de Recursos no Azure - Laboratório Prático

# Descrição  
Este projeto demonstra como configurar e gerenciar o monitoramento de máquinas virtuais (VMs) no Microsoft Azure. O foco está em manter visibilidade, controle e resposta proativa sobre eventos críticos, como a exclusão de VMs, usando ferramentas do Azure Monitor, Log Analytics e Network Watcher.

# Objetivos de Aprendizagem  
- Aplicar os conceitos de monitoramento em um ambiente prático no Azure.  
- Documentar processos técnicos de forma clara e estruturada.  
- Utilizar o GitHub para versionar e compartilhar a documentação.

# Conteúdo do Projeto  
- Configuração do Azure Monitor para máquinas virtuais.  
- Criação e configuração de alertas para eventos críticos.  
- Uso do Log Analytics para coleta e análise de logs.  
- Diagnóstico com Network Watcher.  
- Boas práticas e dicas para monitoramento eficiente.

# Passo a passo do laboratório  

1. **Criar uma VM no Azure**  
   - Acesse o portal do Azure.  
   - Crie uma máquina virtual com as configurações desejadas.

2. **Ativar Azure Monitor e Log Analytics**  
   - Configure um Log Analytics Workspace.  
   - Associe a VM ao workspace para coletar logs e métricas.

3. **Configurar regras de alerta**  
   - Crie alertas para eventos críticos, como exclusão de VM, falhas e alta utilização de CPU.  
   - Defina grupos de ação para notificação (e-mail, webhook, etc.).

4. **Testar alertas e capturar logs**  
   - Realize ações que disparem os alertas.  
   - Verifique as notificações e os logs coletados no Log Analytics.

5. **Analisar os dados coletados**  
   - Use consultas Kusto Query Language (KQL) para analisar os logs.  
   - Extraia insights para melhoria contínua do ambiente.

6. **Documentar aprendizados**  
   - Registre dicas e boas práticas para futuras implementações.  
   - Inclua capturas de tela na pasta `/images` para ilustrar o processo.

# Estrutura do repositório  

#Referências  
- [Azure Monitor Documentation](https://learn.microsoft.com/azure/azure-monitor/)  
- [Log Analytics Overview](https://learn.microsoft.com/azure/azure-monitor/logs/log-analytics-overview)  
- [Network Watcher Documentation](https://learn.microsoft.com/azure/network-watcher/)  
