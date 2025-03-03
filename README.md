# DIO-Bootcamp-Microsoft-Fundamentos-IA-Azure-Analise-de-Sentimentos
Atividade: Análise de Sentimentos com Language Studio no Azure AI

# Passo-a-Passo para Configurar o Azure Language Studio para Análise de Sentimento
## O Azure Language Studio foi substituído pelo Playground de Idiomas no Azure AI Foundry

Acessar o Azure AI Foundry

Abra o Portal do Azure.

Navegue até o Azure AI Foundry, que agora substitui o Azure Language Studio.

No menu do Azure AI Foundry, selecione o "Playground de Idiomas".

## Configurar um Novo Projeto

Dentro do Playground de Idiomas, clique em "Criar novo projeto".

Dê um nome ao projeto e selecione "Análise de Sentimento" como o tipo de análise que você deseja realizar.

## Importar Textos de Amostra

Adicione os textos de amostra que deseja analisar. No seu caso:

### "Toda conquista começa com a decisão de tentar."

### "Só dá errado quando você desiste de fazer dar certo."

### "Para viver seus Sonhos é preciso enfrentar seus MEDOS."

### "VOCÊ é o seu ÚNICO limite."

## Configurar o Analisador de Sentimento

Selecione as configurações padrão ou ajuste as configurações avançadas conforme necessário.

Certifique-se de selecionar a opção que permite a análise detalhada do sentimento em cada frase.

## Executar a Análise

Clique em "Executar análise" para iniciar o processo.

O Playground de Idiomas irá analisar as frases de amostra e fornecer resultados indicando a porcentagem de sentimento positivo, neutro e negativo para cada frase.

# Resultados da Análise de Sentimento

## "Toda conquista começa com a decisão de tentar."

### Resultado da Análise: 72% Positivo; 28% Neutro; 0% Negativo

## "Só dá errado quando você desiste de fazer dar certo."

### Resultado da Análise: 0% Positivo; 0% Neutro; 100% Negativo

## "Para viver seus Sonhos é preciso enfrentar seus MEDOS"

### Resultado da Análise: 3% Positivo; 0% Neutro; 97% Negativo

## "VOCÊ é o seu ÚNICO limite."

### Resultado da Análise: 1% Positivo; 99% Neutro; 1% Negativo

# Insights e Possibilidades

## Insights sobre os Resultados Inesperados

Apesar de todas as frases serem motivacionais, a análise de sentimento realizada pelo Azure AI Foundry pode ter produzido resultados inesperados devido a vários fatores:

Palavras com Conotações Negativas: A presença de palavras como "errado", "desiste", "medos" e "limite" pode ter influenciado a análise, levando a IA a interpretar essas palavras como indicadores de sentimentos negativos, mesmo em um contexto motivacional.

### Contexto Limitado: 
A IA pode não ter captado o contexto positivo geral das frases, focando-se mais nas palavras individuais.

### Neutro vs. Positivo: 
Algumas frases podem ter sido interpretadas como neutras em vez de positivas devido à falta de palavras que expressam claramente otimismo ou entusiasmo.

## Possibilidades e Usabilidade
Melhoria Contínua: Os resultados da análise podem ser utilizados para ajustar e melhorar a precisão dos modelos de IA, considerando o contexto e as nuances das frases motivacionais.

### Aplicações em Negócios: 
A análise de sentimento pode ser aplicada para entender melhor a opinião dos clientes sobre produtos e serviços, ajudando empresas a tomar decisões mais informadas.

### Monitoramento de Redes Sociais: 
A análise de sentimento pode monitorar redes sociais e outras plataformas para identificar tendências e reações do público em tempo real.

### Saúde Mental: 
Ferramentas de análise de sentimento podem ser usadas em aplicativos de saúde mental para detectar e responder a sinais de angústia emocional em textos escritos por usuários.

# Aprendizado adquirido

Durante o processo de configuração do Playground de Idiomas no Azure AI Foundry para realizar uma análise de sentimento, aprendi a importância de entender as nuances das frases analisadas. As etapas envolvem desde a configuração inicial do projeto até a interpretação dos resultados da análise. A realização dessa análise me proporcionou uma visão valiosa sobre como a IA processa o texto e os desafios associados à análise de sentimento, especialmente em frases motivacionais.

Os resultados inesperados reforçaram a necessidade de considerar o contexto e a escolha das palavras ao analisar sentimentos. Também percebi as inúmeras possibilidades e aplicações práticas dessa ferramenta em diversas áreas, como negócios, monitoramento de redes sociais e saúde mental. No geral, essa experiência educativa me ajudou a compreender melhor as capacidades e limitações da análise de sentimento baseada em IA.
