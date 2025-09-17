🌊 API-AGUA-INDIA - Análise de Qualidade da Água na Índia
https://img.shields.io/badge/Python-3.8%252B-blue
https://img.shields.io/badge/Pandas-Data%2520Processing-orange
https://img.shields.io/badge/Architecture-Medalh%C3%B5es%2520(Bronze--Prata--Ouro)-green
https://img.shields.io/badge/Visualization-PowerBI-yellow

Projeto completo de Engenharia de Dados para análise da qualidade da água na Índia, envolvendo ETL, tratamento de dados e criação de dashboard analítico.

📊 Estrutura do Projeto
text
API-AGUA-INDIA/
│
├── 📁 data/
│   ├── 📁 bronze/              # Dados brutos extraídos
│   │   └── Indian_water_data.csv
│   │
│   ├── 📁 prata/               # Dados tratados e processados
│   │   ├── agua_prata_raw.csv
│   │   ├── agua_prata_tratado.csv
│   │   ├── aguaPrataMediasRaw.csv
│   │   └── devprataRaw.ipynb
│   │
│   └── 📁 gold/                # Dados refinados para análise
│       ├── agua_gold_flagsBI.csv
│       └── agua_gold_mediasML.csv
│
├── 📋 requirements.txt         # Dependências do projeto
├── 📖 README.md               # Documentação
└── 🐍 .gitignore              # Arquivos ignorados pelo Git
🏗️ Arquitetura de Medalhões
🥉 Camada Bronze - Dados Brutos
Origem: Kaggle (Indian Water Quality Data)

Formato: CSV com dados brutos extraídos

Características: Dados crus, sem tratamento, mantendo fidelidade à fonte

🥈 Camada Prata - Dados Tratados
Processamento: Limpeza, transformação e engenharia de features

Técnicas:

Tratamento de valores missing (NaN)

Cálculo de médias (mínimo + máximo)/2

Normalização de dados

Codificação de variáveis categóricas

🥇 Camada Ouro - Dados Analíticos
Destino: Dashboard e Machine Learning

Produtos:

agua_gold_mediasML.csv: Dados para modelagem preditiva

agua_gold_flagsBI.csv: Dados com flags de qualidade para dashboard