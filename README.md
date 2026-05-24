# Dashboard Financeiro

💼 Dashboard Financeiro — Desempenho Comercial
<p align="left">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge" />
</p>

Dashboard gerencial com visão 360° do desempenho comercial — consolidando faturamento, mix de produtos, distribuição geográfica e comportamento de pagamento dos clientes em um único painel estratégico.

🔗 [Ver Dashboard ao Vivo](https://app.powerbi.com/view?r=eyJrIjoiZmMxNDc0NjktMDJkZi00MWI4LWJhZmYtNzk1ZTVhMmQ3YmRlIiwidCI6IjdiNzZjYWM5LTBkYTQtNGNmZC1hZWY1LWEyNDgyNDI5NmYyMiJ9)

🎯 Objetivo
Oferecer uma visão gerencial e estratégica do desempenho comercial, respondendo às perguntas mais críticas de um negócio: quanto estamos faturando, quais produtos impulsionam o resultado, onde estão nossos clientes e como eles estão pagando.

📋 Visões e Análises do Painel
💰 Faturamento
Acompanhamento da receita por período com análise de tendência, permitindo identificar crescimento, queda ou estabilidade no desempenho comercial ao longo do tempo.
📦 Análise de Produtos
Visão do portfólio com foco em quais produtos mais contribuem para o faturamento — apoiando decisões de mix, precificação e priorização de estoque.
🗺️ Distribuição Geográfica
Mapa e análise regional mostrando onde estão concentrados os clientes e as vendas, essencial para estratégias de expansão, logística e esforço comercial por região.
💳 Comportamento de Pagamento
Análise dos padrões de pagamento dos clientes: formas preferidas, prazos e eventuais padrões de inadimplência — informações críticas para gestão de fluxo de caixa e políticas de crédito.

🧠 Metodologia
Coleta e Tratamento dos Dados

Dados importados e transformados via Power Query
Padronização de campos de localização para uso em mapas
Normalização das categorias de formas de pagamento
Tratamento de datas para análises temporais consistentes

Modelagem

Modelo estrela (Star Schema) com tabela fato de transações e dimensões de cliente, produto, localização, tempo e forma de pagamento
Relacionamentos otimizados para cruzamentos entre as diferentes dimensões


💡 Principais Insights que o Painel Revela

Concentração geográfica: identifica regiões com maior e menor penetração, orientando esforços de expansão
Mix de produtos: mostra quais itens sustentam o faturamento e quais têm participação marginal
Preferência de pagamento: tendências no comportamento de pagamento dos clientes ao longo do tempo
Sazonalidade de faturamento: variações mensais que permitem planejamento mais preciso de metas e recursos


🛠️ Ferramentas Utilizadas
FerramentaUsoPower BI DesktopConstrução do dashboard e visualizaçõesPower QueryETL, tratamento e transformação dos dadosDAXMedidas, KPIs e cálculos de negócioMapas do Power BIVisualização geográfica dos clientesExcelBase de dados fonte
