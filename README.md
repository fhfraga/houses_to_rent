## Projeto de previsão de aluguel de imóveis em cinco cidades diferentes do Brasil

<figure>
  <img src="./imagens/aluguel1.jpg " alt="Figura 1" />
</figure>

## Observações
* Este projeto teve o intuito de simular um cenário para previsões de aluguel em cinco diferentes cidades brasileiras (São Paulo, Rio de Janeiro, Porto Alegre, Belo Horizonte e Campinas)

* Sinta-se à vontade para olhar todo o código e análises feitas.

## Planejamento da solução
1. carregar o conjunto de dados
2. Observar e tratar os dados
3. Criar hipóteses
4. Análisar os dados
5. Validar o rejeitar as hipóteses
6. Analisar a correlação entre as variáveis
7. Preparar os dados
8. Estimar o modelo de aprendizado de máquina
9. Tirar conclusões

## Projeto

Este projeto teve o intuito de fazer a análise de fatores que podem influenciar no aluguel de uma casa em cinco cidades brasileiras. Para isso foi feita uma descrição dos dados, tratamentos dos mesmos,  filtragem das variáveis e análise exploratória de dados, de tal forma que com apenas essas análises podemos criar gráficos como da Figura 1

<figure>
  <img src="./imagens/aluguel2.png " alt="Figura 1" />
  <figcaption>Figura 1. Análise univariada de variáveis categóricas do projeto.</figcaption>
</figure>

A partir dessas etapas fomos especificando na análise exploratória dos dados, criando hipóteses de senso comum sobre aluguel e tentando responder as mesmas com dados, como mostrando na Figura 2.


<figure>
  <img src="./imagens/aluguel3.png " alt="Figura 1" />
  <figcaption>Figura 2. Verificação da hipótese de que residências maiores são mais caras.</figcaption>
</figure>

Depois de verificar diferentes hipóteses entramos na preparação dos dados para criação dos modelos de machine learning. Com essas etapas chegamos a um modelo final de machine learning que nos deu previsões como na Figura 3.

<figure>
  <img src="./imagens/aluguel4.png " alt="Figura 1" />
  <figcaption>Figura 3. Previsão do modelo.</figcaption>
</figure>

o notebook com todas as etapas está [aqui]()

## Conclusão
Podemos concluir que o modelo faz previsões, porém pode se melhorar. As formas de melhores é:
* Conseguir mais dados para treinar o modelo
* Verificar novamente as variáveis para criação de novas ou exclusão para diminuir a dimensionalidade
* Testar outros modelos de aprendizado de máquina