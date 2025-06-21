# 📊 Telecom X - Análise de Churn de Clientes

## 🎯 Visão Geral

Este projeto apresenta uma análise completa de evasão de clientes (churn) da empresa Telecom X, utilizando técnicas de análise exploratória de dados (EDA) e processamento ETL para identificar padrões e fatores que contribuem para a perda de clientes.

## 🔍 Problema de Negócio

A Telecom X vem enfrentando altas taxas de evasão de clientes, impactando diretamente a receita e competitividade da empresa. O objetivo deste projeto é identificar os principais fatores que levam à evasão e fornecer insights acionáveis para estratégias de retenção.

## 📋 Estrutura do Projeto

```
telecom-x-churn-analysis/
│
├── notebooks/
│   └── churn_analysis.ipynb          # Notebook principal com análise completa
├── data/
│   ├── raw/                          # Dados brutos extraídos da API
│   └── processed/                    # Dados processados e limpos
├── src/
│   ├── data_extraction.py            # Scripts para extração de dados
│   ├── data_cleaning.py              # Scripts para limpeza de dados
│   └── visualization.py              # Scripts para visualizações
├── reports/
│   └── churn_analysis_report.md      # Relatório final da análise
└── README.md
```

## 🛠️ Tecnologias Utilizadas

- **Python 3.8+**
- **Pandas** - Manipulação e análise de dados
- **NumPy** - Computação numérica
- **Matplotlib** - Visualização de dados
- **Seaborn** - Visualizações estatísticas
- **Jupyter Notebook** - Ambiente de desenvolvimento

## 📊 Principais Descobertas

### Taxa de Evasão
- **25%** dos clientes abandonaram a empresa
- Concentração em contratos mensais (**88.6%** dos clientes evasivos)
- **57%** dos clientes evasivos utilizavam cheque eletrônico como método de pagamento

### Fatores de Retenção
- Contratos de longa duração (1-2 anos) apresentam maior fidelidade
- Clientes com maior tempo de permanência tendem a gastar mais
- Idade não se mostrou um fator determinante para evasão

## 🚀 Como Executar

### Pré-requisitos
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Execução
1. Clone este repositório:
```bash
git clone https://github.com/seu-usuario/telecom-x-churn-analysis.git
cd telecom-x-churn-analysis
```

2. Instale as dependências:
```bash
pip install -r requirements.txt
```

3. Execute o notebook principal:
```bash
jupyter notebook notebooks/churn_analysis.ipynb
```

## 📈 Processo de Análise

### 1. Extração de Dados (Extract)
- Conexão com API da empresa
- Coleta de dados de clientes e contratos
- Validação da integridade dos dados

### 2. Transformação de Dados (Transform)
- Limpeza de valores nulos e inconsistentes
- Conversão de variáveis categóricas para binárias
- Criação de variáveis derivadas (ex: gasto diário)
- Otimização de tipos de dados

### 3. Análise Exploratória (Load & Analyze)
- Análise descritiva das variáveis
- Identificação de padrões de churn
- Visualizações comparativas
- Correlações entre variáveis

## 💡 Recomendações Estratégicas

### Foco em Contratos de Longa Duração
Desenvolver campanhas promocionais para migração de contratos mensais para anuais/bianuais, oferecendo benefícios como descontos progressivos e serviços adicionais.

### Diversificação de Métodos de Pagamento
Implementar programas de incentivo para migração do cheque eletrônico para métodos automáticos de pagamento, reduzindo friction e aumentando conveniência.

### Programa de Fidelidade
Criar sistema de recompensas para clientes de longa data, estabelecendo barreiras emocionais e financeiras para evasão.

## 📊 Métricas de Impacto

- **Redução potencial de 15-20%** na taxa de churn
- **Aumento estimado de 25%** no valor vitalício do cliente (CLV)
- **ROI projetado** de 300% em ações de retenção


## 👥 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:
- Reportar bugs
- Sugerir melhorias
- Propor novas análises
- Otimizar código existente

## 📧 Contato

Para dúvidas ou sugestões, entre em contato:
- **Email**: victorjcldev@outlook.com
- **LinkedIn**: [www.linkedin.com/in/victorjcl)
