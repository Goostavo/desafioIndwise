# Desafio indWise

## Desafio 0 - Git básico
Faça um fork deste repositório e comece a trabalhar com seu código!

## Desafio 1 - Análise de dados
Baixe o arquivo JSON **producao.json**
Este arquivo contém a produção de uma fábrica ao longo de uma semana.
Cada entrada do vetor de dados contém o timestamp, indicando que um produto foi produzido.

Faça uma análise exploratória dos dados utilizando a ferramenta que quiser. Gera um gráfico de visualização de produção por dia. Você também pode extrair algum indicador implícito ou apenas cria uma visualização interessante dos dados. Criar algo novo a partir dos dados é a parte mais legal do desafio!

No site Kaggle podem ser vistos vários exemplos de análises de dados
https://www.kaggle.com/kaggle/us-baby-names

Descrição dos dados do arquivo **producao.json**:

Campos necessários:
- **pt** (Production time) : Horário em que foi produzido uma unidade do produto

Outros campos:
- **ri** (Radio Id) : Identificador do rádio que gerou os dados (sempre será 1, pois pegamos apenas de uma máquina).
- **uuid** (unique id): Identificador único gerado pelo gerador de analytics
- **sis** (Speed in Seconds) : Tempo entre a produção atual e a anterior em segundos
- **id** : Identificador único do mongodb
- **createdAt** : Horário que dado foi criado no banco de dados
- **updatedAt** : Horário da última atualizçaão no banco de dados

## Desafio 2 - Conhecimento web
Utilizando os frameworks de sua preferência crie uma visualização de dados para mostrar a soma da produção por dia dos dados producao.json

Utilize bibliotecas de visualização que disponham de efeitos visuais como gráficos e capriche no CSS (mesmo que for utilizando um template pronto).

Se possível implemente um código que disponha de um backend separado, utilizando frameworks como sails, rails e laravel.
