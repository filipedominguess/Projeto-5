# Projeto de Análise de Vendas de Jogos da Loja Online Ice

## Objetivo do Projeto 
Identificar padrões que determinam o sucesso de jogos vendidos pela loja online ice e planejar campanhas publicitárias para potenciais grandes vencedores.

## Dados Utilizados 
games.csv contendo avaliações de usuários e especialistas, gêneros, plataformas e dados históricos sobre vendas de jogos.

## Preparação dos Dados

- Substituição dos nomes das colunas para minúsculos.
- Conversão dos dados para os tipos necessários, alterando as colunas onde necessário.
- Tratamento de valores ausentes conforme a análise do contexto dos dados.
- Cálculo do total de vendas em todas as regiões para cada jogo.

## Análise dos Dados

- Identificação da quantidade de jogos lançados em anos diferentes e avaliação da significância dos dados para cada período.
- Verificação da variação de vendas de plataforma para plataforma e construção de distribuições para plataformas com maiores vendas totais. Identificação de plataformas antigas que não têm vendas e avaliação do tempo para o surgimento de novas plataformas.
- Seleção dos dados relevantes para construir um modelo para 2017 e identificação das plataformas líderes em vendas, bem como as plataformas potencialmente lucrativas.
- Construção de um diagrama de caixa para as vendas globais de todos os jogos, divididos por plataforma, e análise da significância das diferenças nas vendas.
- Verificação da relação entre as avaliações de usuários e profissionais e as vendas de uma plataforma popular, construção de um gráfico de dispersão e cálculo da correlação entre revisões e vendas. Comparação das vendas dos mesmos jogos em outras plataformas.
- Análise da distribuição geral de jogos por gênero e identificação dos gêneros mais lucrativos e generalização sobre gêneros com vendas altas e baixas.
- Criação de um perfil de usuário para cada região, identificação das cinco plataformas principais e variações das suas quotas de mercado de região para região. Identificação dos cinco principais gêneros e explicação das diferenças. Verificação se as classificações do ESRB afetam as vendas em regiões individuais.

## Teste de Hipóteses

- Teste da hipótese de que as classificações médias dos usuários das plataformas Xbox One e PC são as mesmas.
- Teste da hipótese de que as classificações médias de usuários para os gêneros Action e Sports são diferentes.
- Valor do Limiar Alfa: Será definido pelo analista.

Fórmula das hipóteses alternativas e nulas:
- Hipótese nula H0: as classificações médias dos usuários das plataformas Xbox One e PC são iguais.
- Hipótese alternativa H1: as classificações médias dos usuários das plataformas Xbox One e PC são diferentes.
- Hipótese nula H0: as classificações médias de usuários para os gêneros Action e Sports são iguais.
- Hipótese alternativa H1: as classificações médias de usuários para os gêneros Action e Sports são diferentes.

## Descrição de dados
* `Name` (nome)
* `Platform` (plataforma)
* `Year_of_Release` (ano de lançamento)
* `Genre` (gênero)
* `NA_sales` (vendas norte-americanas em milhões de USD)
* `EU_sales` (vendas na Europa em milhões de USD)
* `JP_sales` (vendas no Japão em milhões de USD)
* `Other_sales` (vendas em outros países em em milhões de USD)
* `Critic_Score` - (pontuação crítica) (máximo de 100)
* `User_Score` - (pontuação do usuário) (máximo de 10)
* `Classificação` (ESRB)

Os dados de 2016 podem estar incompletos.
