# Projeto-de-BI-Gestao-de-Atendimento
Este projeto consiste em um dashboard desenvolvido no Power BI para analisar indicadores de um sistema de Help Desk. O foco foi estruturar métricas e eficiência para uma empresa de sustentação de TI em Brasília.

🛠️ Tecnologias Utilizadas
Power BI: Modelagem, Visualização e DAX.

Power Query: ETL (Extração, Transformação e Carga).

📊 Principais Métricas (DAX)
Total de Tickets: COUNT

% Tickets Críticos: DIVIDE(CALCULATE(), COUNT()

Tickets Aguardando Cliente: CALCULATE(Status = "Aguardando Resposta do Cliente")

📈 Insights e Plano de Ação

1. Redução do Gargalo de Pendências Externas

O dashboard indica que 2,88 mil tickets estão parados aguardando o cliente, disparar lembretes automáticos via e-mail e chat após 24h e 48h de inatividade do cliente.

2. Mitigação de Incidentes Críticos

Software Bug é o principal motivo de abertura de chamados, e a prioridade Crítico representa 25,14% da demanda,exportar os dados de Assunto do Ticket para a equipe de desenvolvimento priorizar o bugfix nos módulos mais afetados, reduzindo a entrada de novos tickets críticos na origem.

3. Planejamento de Capacidade

Identificação de picos de demanda acima de 700 tickets em Janeiro, Julho e Outubro, reforçar o time de suporte nesses meses específicos durante esses picos para garantir que o tempo de resposta não seja ultrapassado.

📸 Visualização do Dashboard

<img width="1254" height="680" alt="Captura de tela 2026-03-01 150638" src="https://github.com/user-attachments/assets/5273a2ca-c2b5-4da9-be91-247ef4cf3633" />
