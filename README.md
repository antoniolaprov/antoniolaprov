## Antônio Laprovitera

Estudante de Ciência da Computação na CESAR School (Recife, 5º período).
Trabalho com dados de ponta a ponta: da ingestão de fontes públicas
brasileiras até modelos de machine learning que rodam em produção, com
validação, testes e retreino agendado.

Hoje estou focado em **ML aplicado a dados tabulares e séries temporais**:
como avaliar um modelo sem vazar o futuro, como saber se ele ganha de um
baseline simples e como mantê-lo funcionando quando o dado muda.

### Projetos

**[AgroClima Analytics](https://github.com/antoniolaprov/agroclima-analytics)**
Prevê a anomalia de rendimento de soja, milho, café e cana por estado a
partir do clima observado no ciclo (INMET 2001–2026 + IBGE/PAM).
- Alvo e normais climáticas calculados só com anos anteriores, sem vazamento
- Validação temporal (rolling origin), skill contra a tendência com IC 95% por bootstrap de anos
- Baselines, ablações e previsão antecipada com 1/3 e 2/3 do ciclo observado; LightGBM + SHAP
- Retreino no Airflow só quando o dado muda, com portão de promoção e tracking no MLflow
- Pipeline Bronze/Silver/Gold com dbt + DuckDB, dashboard Streamlit e site em Next.js

**[FinBrasil Analytics](https://github.com/antoniolaprov/finbrasil-analytics)**
Pipeline diário de indicadores macroeconômicos (SELIC, IPCA, câmbio, PIB,
desemprego) a partir das APIs do Banco Central e do IBGE, com Airflow, dbt,
DuckDB e dashboard.

**[Poste de iluminação inteligente](https://github.com/antoniolaprov/g17-iluminacao-inteligente)**
Sistemas Embarcados: poste conectado que ajusta a potência pela presença na
rua e avisa a central quando a lâmpada falha.

**[OdontoHub](https://github.com/antoniolaprov/OdontoHub)**
Gestão de clínicas odontológicas com DDD e Arquitetura Limpa.

### Ferramentas

**ML e dados:** Python, pandas, scikit-learn, LightGBM, MLflow, SQL, dbt, DuckDB, Airflow
**Desenvolvimento:** Java, Spring Boot, C, TypeScript, Next.js, Docker, Git

### Contato

[LinkedIn](https://www.linkedin.com/in/ant%C3%B4nio-laprovitera-aba7aa36a/)
