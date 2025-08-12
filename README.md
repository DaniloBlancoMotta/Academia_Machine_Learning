# 🏋️‍♂️ Modelo Preditivo de Churn para Academia
> Análise e previsão de cancelamento de clientes em academia utilizando Machine Learning

## 📋 Sobre o Projeto
Este projeto desenvolve um modelo preditivo para identificar potenciais cancelamentos de clientes em uma academia, utilizando técnicas avançadas de machine learning. O modelo alcançou uma precisão superior a 76% após refinamentos.

### 🎯 Objetivos
- Identificar padrões de comportamento que levam ao cancelamento
- Prever possíveis cancelamentos com alta precisão
- Fornecer insights acionáveis para retenção de clientes

## 🛠️ Tecnologias Utilizadas

- Python 3.8+
- Pandas
- Scikit-learn
- XGBoost
- Seaborn
- Matplotlib

## 📊 Dataset
O dataset contém informações sobre:
- Kaggle (USA_Gyms)
- Dados demográficos dos clientes
- Histórico de frequência
- Padrões de uso
- Informações contratuais
- Status de cancelamento

## 🚀 Como Usar

### Pré-requisitos
```bash
pip install -r requirements.txt
```

### Estrutura do Projeto
```
├── Academia.ipynb          # Notebook principal com análises
├── gym_churn_us.csv       # Dataset
├── requirements.txt       # Dependências
└── README.md             # Documentação
```

### Executando o Modelo
1. Clone o repositório
```bash
git clone [URL_DO_REPOSITÓRIO]
```

2. Instale as dependências
```bash
pip install -r requirements.txt
```

3. Abra o notebook `Academia.ipynb`
```bash
jupyter notebook Academia.ipynb
```

## 📈 Resultados

### Performance do Modelo
- R² Score: 0.76
- Precisão na identificação de churn
- Capacidade de previsão antecipada

### Principais Insights
1. **Frequência de Uso**
   - Principal indicador de retenção
   - Correlação negativa forte com cancelamento

2. **Tempo como Cliente**
   - Período crítico nos primeiros 3 meses
   - Estabilização após 12 meses

3. **Fatores de Engajamento**
   - Importância das atividades em grupo
   - Impacto do suporte social

## 📊 Visualizações
O projeto inclui visualizações detalhadas de:
- Padrões de frequência
- Correlações entre variáveis
- Importância das features
- Matriz de correlação

## 💡 Insights Acionáveis

### Programa de Onboarding
- Foco nos primeiros 90 dias
- Acompanhamento personalizado
- Metas progressivas

### Estratégia de Retenção
- Sistema de alertas preventivos
- Intervenções baseadas em dados
- Programas de fidelidade

### Desenvolvimento de Produto
- Expansão de atividades em grupo
- Pacotes personalizados
- Benefícios progressivos

## 📄 Licença
Este projeto está sob a licença MIT.


