# Previsão de Preços de Carros

## 📋 Descrição do Projeto
O objetivo é realizar predições em um aplicativo de vendas de carros. A qualidade e velocidade de predições é crucial para o negócio. O projeto utiliza dados históricos, especificações técnicas, versões de acabamento e preços.

## 🛠️ Ferramentas e Bibliotecas Utilizadas
- Python: Linguagem principal utilizada para a análise
- Pandas: Manipulação e análise de dados
- Numpy: Manipulação e análise de dados
- Sklearn: Construção de modelo de machine learning
- lightgbm: Construção de modelo de machine learning
- Matplotlib.pyplot e Seaborn: Construção de gráficos
- Time: Metrificar tempo de execução

## 📊 Estrutura dos Dados
O conjunto de dados possui os seguintes campos:
- `DateCrawled`: Data em que o perfil foi baixado do banco de dados
- `VehicleType`: Tipo de carroçaria do veículo
- `RegistrationYear`: Ano de matrícula do veículo
- `Gearbox`: Tipo de caixa de transmissão
- `Power`: Potência (hp)
- `Model`: Modelo do veículo
- `Mileage`: Quilometragem (km)
- `RegistrationMonth`: Mês de registro do veículo
- `FuelType`: Tipo de combustível
- `Brand`: Marca do veículo
- `NotRepaired`: Veículo reparado ou não
- `DateCreated`: Data de criação do perfil
- `NumberOfPictures`: Número de fotos do veículo
- `PostalCode`: Código postal do proprietário
- `LastSeen`: Data da última atividade do usuário
- `Price`: Preço (Euro)

## 🔍 Metodologia

### 1. Análise Exploratória de Dados
- Importação das bibliotecas necessárias
- Carregamento e visualização dos dados

### 2. Pré-processamento
- Tratamento de dados ausentes
- Remoção de dados duplicados

### 3. Preparação
- Codificação de rótulos
- Seleção de features e target
- Divisão entre base de teste e treino

### 4. Criação de Modelos
- Calibração de hiperparâmetros
- Implementação dos modelos:
  - LightGBM
  - Floresta Aleatória
  - Árvore de Decisão
  - Regressão Linear
- Análise das métricas

## 📈 Resultados
Para este projeto usamos os modelos de lightGBM, Floresta Aleatória, Árvore de Decisão e Regressão Linear para decidir qual o melhor modelo para nosso conjunto de dados. Testamos diferentes parâmetros no modelo lightGBM que variaram muito o tempo de execução do mesmo, por isso deixei o que está no projeto. Além de medir o tempo de execução de cada modelo avaliamos todos eles pelo REQM, e por isso, podemos escolher o modelo lightGBM como o melhor para essa tarefa, por mais que ele tenha o maior tempo de execução, é acetável.

## 📚 Aprendizados
1. Análise de dados e extração de insights
2. Preparação de dados para Machine Learning
3. Aplicação de regras de negócios
4. Implementação de modelos de Machine Learning
5. Documentação detalhada de projetos
6. Utilização do ecossistema Python
7. Tomada de decisões baseada em dados

## Aprendizados
* Análise de dados: Extração de insights valiosos a partir de grandes volumes de dados.
* Preparação para Machine Learning: Separação entre conjuntos de treino e teste, seleção de features.
* Aplicação de modelos de Machine Learning: Ajuste, avaliação e documentação.
* Tomada de decisões baseadas em dados: Uso de insights para decisões estratégicas.


https://projeto-vehicles-5.onrender.com


