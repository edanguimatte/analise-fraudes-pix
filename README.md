# analise-fraudes-pix
Análise de vulnerabilidade a fraudes financeiras digitais no Brasil, focada no sistema PIX. O projeto utiliza análise de dados para identificar padrões e propor soluções de segurança
### Objetivo do Projeto

* Identificar padrões de fraude e os principais tipos de golpes (phishing, clonagem de WhatsApp, etc.).
* Mapear as populações e regiões mais suscetíveis a fraudes financeiras.
* Correlacionar fatores demográficos (idade, renda, escolaridade) com a incidência de golpes.
* Fornecer insights estratégicos para que bancos, órgãos públicos e ONGs possam direcionar campanhas de prevenção e educação digital de forma mais eficaz.

### Fontes de Dados

As análises foram baseadas em dados públicos e não confidenciais, incluindo:

* **Banco Central do Brasil:** Relatórios de fraudes e dados de transações suspeitas.
* **IBGE:** Dados demográficos (renda, escolaridade, acesso à internet).
* **Relatórios de Cibersegurança:** Informações e tendências de fraudes disponibilizadas em artigos de empresas do setor.

### Metodologia

O projeto seguiu as seguintes etapas:

1.  **Coleta de Dados:** Levantamento de fontes de dados públicas através de APIs e downloads diretos.
2.  **Análise Exploratória (EDA):** Análise inicial dos dados para identificar padrões, tendências e anomalias.
3.  **Modelagem de Dados:** Criação de modelos para prever riscos e classificar transações.
4.  **Visualização de Dados:** Desenvolvimento de dashboards e gráficos interativos para comunicar os insights de forma clara.

### Resultados e Insights

A análise exploratória revelou insights cruciais sobre as vulnerabilidades:

* **Perfil Etário:** Indivíduos acima de 60 anos, embora representem uma pequena parcela de usuários do PIX, são desproporcionalmente afetados por golpes de contato direto.
* **Escolaridade:** Estados com maior taxa de analfabetismo tendem a ser mais vulneráveis a fraudes, pois a falta de letramento digital reduz a capacidade de prevenção.
* **Renda:** Populações de baixa renda são alvo de golpes de baixo valor, enquanto classes mais altas podem sofrer golpes mais sofisticados.
* **Tendência Temporal:** O aumento expressivo de fraudes geralmente ocorre em períodos de lançamento de novos aplicativos ou campanhas bancárias.
* **Taxa de Recuperação:** Embora muitos casos sejam contestados, a taxa de recuperação de valores ainda é baixa, evidenciando gargalos no processo de atendimento e resposta das instituições financeiras.
* **Segmentação de Risco:** A combinação de fatores como baixa escolaridade, faixa etária avançada e baixa renda cria "clusters de vulnerabilidade", permitindo ações preventivas mais direcionadas.

### Tecnologias Utilizadas

* **Linguagem de Programação:** Python
* **Bibliotecas:** Pandas, Matplotlib, Seaborn
* **Visualização:** Looker Studio, Jupyter Notebook

### Como Executar o Projeto

Para replicar este projeto, clone o repositório e execute os scripts na ordem:

1.  Execute `scripts/01_coleta_e_limpeza.py` para processar os dados brutos.
2.  Execute `scripts/02_analise_e_modelagem.py` para rodar as análises.
3.  Abra `scripts/03_visualizacao.ipynb` para visualizar os gráficos e a análise completa.
