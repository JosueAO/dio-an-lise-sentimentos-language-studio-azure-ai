# dio-an-lise-sentimentos-language-studio-azure-ai
 DIO(Digital Innovation One) Análise de Sentimentos com Language Studio no Azure AI

# Projeto de Análise de Sentimentos com Azure Language Studio

Neste projeto, eu demonstro como utilizar o Azure Language Studio para realizar uma análise de sentimentos em várias sentenças. O objetivo principal é identificar e entender os sentimentos expressos em cada sentença, explorando as capacidades de análise de texto da plataforma Azure AI.

## Estrutura do Repositório

- `/inputs`: Esta pasta contém o documento `sentences.txt` com as sentenças que eu preparei para análise.
- `/outputs`: Aqui, eu salvo os resultados da análise de sentimentos (opcional, dependendo de como você deseja documentar os resultados).

## Configuração do Ambiente

Inicialmente, configurei minha conta no Azure e acessei o Azure Portal para criar um recurso de Language Service. Este recurso é essencial para acessar as funcionalidades de análise de texto oferecidas pelo Azure Language Studio.

## Preparação dos Dados de Entrada

Dentro da pasta `inputs`, criei um arquivo chamado `sentences.txt`, onde escrevi várias sentenças que refletem diferentes emoções para testar a eficácia do serviço de análise de sentimentos.

## Processo de Análise

Utilizei a API de análise de texto do Azure para enviar as sentenças do arquivo `sentences.txt`. Eu configurei a chamada à API para que ela processasse e analisasse os sentimentos expressos nas sentenças. Esta etapa foi crucial para entender como diferentes expressões emocionais são interpretadas pela inteligência artificial.

## Resultados e Insights

Os resultados foram muito bom. Os testes mostraram claramente como a tecnologia Azure AI interpreta variações sutis na linguagem para determinar sentimentos. Este insight é extremamente valioso, especialmente em aplicações como atendimento ao cliente ou monitoramento de redes sociais, onde entender a emoção do cliente é crucial.

## Prints do Projeto

Aqui estão algumas capturas de tela do processo de configuração, da interface do Azure ML e dos resultados obtidos. Essas imagens ajudam a visualizar como o projeto foi realizado do início ao fim.

- ![Configuração do Ambiente](/images/setup.png)
- ![Análise de Sentimentos](/images/sentiment_analysis.png)
- ![Resultados](/images/results.png)

Eu espero que este documento ajude outros desenvolvedores e entusiastas da AI a replicar ou adaptar este projeto para suas próprias necessidades. A análise de sentimentos é uma ferramenta poderosa, e o Azure Language Studio oferece uma forma acessível e eficiente de aproveitar essa tecnologia.
