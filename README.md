# Beta Bank Churn Prediction  

## Descrição  

Este projeto tem o objetivo de realizar a criação de um modelo de classificação para prever se um cliente do Beta Bank tende a deixar o banco em breve. Utilizando dados sobre o comportamento passado dos clientes e rescisões de contratos, o modelo deve alcançar um F1-score mínimo de 0,59. Além disso, a métrica AUC-ROC será medida e comparada com o F1-score.  

## Instalação  

### Pré-requisitos
**Python 3.x**: (Qualquer versão do Python 3, como 3.6, 3.7, 3.8, etc.)  

**Bibliotecas Python** 
* pandas
* numpy
* scikit-learn
* matplotlib
* re  

### Instruções de Instalação
1.	**Clone o repositório:** git clone https://github.com/Rosental14/Beta_Bank.git
2.	**Navegue até o diretório do projeto**
3.	**Instale as dependências: pip install -r requirements.txt**

## Uso
1. **Abra o Jupyter Notebook**
2. **Navegue até o arquivo** projeto_beta_bank.ipynb e abra-o.
3. **Execute as células sequencialmente para reproduzir a análise e a criação do modelo.**  

## Funcionalidades  

### Etapas Iniciais
* Importação de Bibliotecas;  
* Leitura dos Dados;   
* Informações Gerais.   

### Preparação dos Dados
* Conversão de Tipos de Dados;  
* Tratamento de Dados Ausentes;  
* Codificação de Variáveis Categóricas;  
* Normalização e Padronização.  
 
### Divisão dos Dados
* **Divisão em Conjuntos:** Divisão dos dados em conjuntos de treinamento, validação e teste na proporção 60:20:20.
* **Características e Objetivo:** Definição das colunas de características e do objetivo.  

### Estudo do Melhor Modelo  

* **Árvore de Decisão:** Avaliação de diferentes hiperparâmetros.
* **Floresta Aleatória:** Avaliação de diferentes hiperparâmetros.
* **Regressão Logística:** Avaliação do desempenho do modelo.  

### Correção do Desequilíbrio de Classes
* **Técnicas:** Superamostragem, Ajuste de Limiar e Ajuste de Ponderação de Classes;
* **Avaliação dos Modelos:** Comparação dos resultados obtidos após a utilização das técnicas de correção.  

### Avaliação Final
* **Teste do Melhor Modelo:** Avaliação do modelo final no conjunto de teste.
* **Métricas de Avaliação:** Cálculo do F1-score e da métrica AUC-ROC, além da Curva ROC, Curva PR e Matriz de Confusão.
* **Comparação de Resultados:** Análise comparativa das métricas de desempenho.

## Créditos
* **Autor:** Renan Rosental  

## Contato
Para dúvidas e feedback, entre em contato via e-mail: renan.engal@gmail.com
