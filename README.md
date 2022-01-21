# Properties_Occupation
Analisar dados de ocupação e preço de anúncios no Airbnb

<p>  <br>
  </p>
  
# Índice
- [Solicitações](README.md#Solicitações)
- [Objetivos](README.md#Objetivos)
- [Linguagem](README.md#Linguagem)
- [Análises](README.md#Análises)
- [Conclusões](README.md#Conclusões)
- [**Arquivo em Python**](Seazone_Data_Analysis.ipynb)

<p>  <br>
  </p>
  
# Solicitações
Foi solicitado uma análise de dados de ocupação e preço de anúncios no Airbnb

<p>  <br>
  </p>
  
# Objetivos
Como objetivo, foi proposto ordenar os dados e responder algumas perguntas:
- 1º)  Ordene os bairros em ordem crescente de número de listings
- 2º)  Ordene os bairros em ordem crescente de faturamento médio dos listings
- 3º)  Existem correlações entre as características de um anúncio e seu faturamento?
      a. Quais? Explique
- 4º)  Qual a antecedência média das reservas?
      a. Esse número é maior ou menor para finais de semana?     

<p>  <br>
  </p>
  
# Linguagem
Análise realizada com Python

Foram disponibilizados dois arquivos .csv para as análises.
- desafio_details.csv (4.691 registros)
- desafio_priceav.csv (354.520 registros)
- O Período analisado está entre 02/11/2020 e 30/03/2021
- Foram utilizadas as seguintes bibliotecas do Python:
    - Pandas
    - Numpy
    - Matplotlib
    - Datetime
 - Foram efetuados os seguintes comandos para:
    -  Agrupar, Somar, Contar, Ordenar e Média dos registros (groupby, sum, count, sort_values, mean)
    -  Criar e editar gráficos (plot, xlabel, title, etc...)
    -  Alterar tipos de dados e trocar dados nulos (astype, str.replace) 
    -  Filtrar Dados (loc)
    -  Criar colunas calculadas (operador matemático de menos)
    -  Extrair datas dos dias da semana (dt.day_name)
    -  Extrair números inteiros de coluna timedelta64 (dt.days)
    -  Ordenar dados com comando categorias do pandas (pd.Categorical)

<p>  <br>
  </p>
  
# Análises
> ## Primeira Solicitação
Dados agrupados por bairro (suburb), e ordenados por número do anúncio (listing)

![**imagem**](first_question1.png)

<p>  <br>
  </p>
  
> ## Segunda Solicitação
Dados agrupados por bairro (suburb), e ordenados pelo faturamento médio (price_string), do menor para o maior valor

Obs: Neste gráfico podemos observar que o bairro Jurerê tem o maior faturamento médio no período

![**imagem**](second_question2.png)

<p>  <br>
  </p>
  
![**imagem**](second_question.png)

<p>  <br>
  </p>
  
> ## Terceira Solicitação
Dados agrupados por bairro (suburb) e por avaliações (star_rating), somando o valor de faturamento.

Obs: Neste gráfico podemos observar que quanto melhor a avaliação do imóvel, maior é o faturamento total.

Considerando que quanto melhor é a avaliação, maior é o faturamento com locações, podemos afirmar que existe relação direta com as características do imóvel.

![**imagem**](third_question.png)

<p>  <br>
  </p>
  
> ## Quarta Solicitação
A média apurada de antecedência no período analisado foi de 38 dias (arredondando o resultado).

Ao observar o gráfico abaixo, podemos considerar que praticamente não existe diferença de antecedência entre os dias da semana.

![**imagem**](fourth_question.png)

<p>  <br>
  </p>
  
> ## Conclusões
Após análise dos dados, podemos concluir que:
    - O bairro Ingleses tem o maior número de anúncios
    - O bairro Ingleses tem o maior faturamento total, e o segundo melhor faturamento médio
    - O bairro Jurerê tem o maior faturamento médio
    - O bairro Centro tem o menor faturamento total e o menor faturamento médio

<p>  <br>
  </p>
  
> ## Autor do Projeto
Projeto Realizado por Richard Gomes de Araújo em Janeiro/2022
- [**Linkedin**](https://www.linkedin.com/in/richardaraujoanalistadedados/)




      
 




