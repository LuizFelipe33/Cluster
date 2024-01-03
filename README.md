# Projeto de Análise de Dados de Países

## Descrição
Este projeto analisa dados de países, aplicando técnicas de pré-processamento, clusterização com KMeans e DBSCAN, visualização com gráficos de silhueta e PCA (Principal Component Analysis).

## Objetivo
Explorar padrões e agrupamentos em dados de países para fornecer insights sobre características similares.

## Metodologia
1. **Coleta de Dados:**
   - Dados foram obtidos incluindo informações sobre indicadores sociais, econômicos e demográficos.

2. **Pré-processamento de Dados:**
   - Utilização de Standard Scaler para normalização dos dados.
   - Tratamento de valores ausentes e seleção de features relevantes.

3. **Modelagem com KMeans:**
   - Aplicação do algoritmo KMeans para identificar clusters de países.
   - Avaliação dos clusters utilizando gráficos de silhueta.

4. **Visualização com PCA:**
   - Redução de dimensionalidade com PCA para visualização em duas dimensões.
   - Análise de variância explicada para seleção de componentes principais.

5. **Modelagem com DBSCAN:**
   - Utilização do DBSCAN para identificar clusters baseados na densidade.
   - Ajuste de hiperparâmetros para otimizar a clusterização.

## Resultados
A análise revela agrupamentos naturais entre países, oferecendo insights sobre semelhanças e diferenças em indicadores sociais e econômicos.

## Tecnologias Utilizadas
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
