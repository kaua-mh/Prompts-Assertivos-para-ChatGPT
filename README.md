
# Prompts assertivos para ChatGPT

## Primeiro - O que são Prompts?
- É todo comando que você digita ou até mesmo os comandos que se manda no ChatGPT são considerados Prompts
- É uma caixa que recebe parâmetros, sua pergunta é um parâmentro mas você pode passar um conjunto de parâmetros

## Técnica FTAE
- Se resume a um modelo de perguntas no caso F - função / T - tipo de texto / A - Assunto / E - estilo
- Função: (Escreva/Resuma/Traduza/Crie Topicos)
- Tipo de texto: (Roteiro/Post para blog/Artigo/Poema/Postagem no instagram)
- Assunto: (I.A/Futebol,Música,Filme...etc)
- Estilo: (Personagem,Escritor,Filósofo)

## Variáveis Semânticas
- Você pode passar regras e variáveis para a I.A

## Técnica dos 3R's
- Resumo, Roteiro e as Regras

## Como falar para o ChatGPT que tem campos semânticos?
- Ex: 
`Agora, use os itens em {RESUMO} para o {ROTEIRO} seguindo as {REGRAS}`

`{RESUMO}`

`{ROTEIRO}`

`{REGRAS}`
- obs: Os campos precisam ter o mesmo nome entre chaves

- Para declarar uma autoridade se usa [ ], por exemplo:
`{RESUMO}`\
`[Autoridade]: Felipe, um desenvolvedor Fullstack`\
`[Avatar]: Desenvolvedores Júniors` \
`[Problema]: Como instalar o Docker`

`{ROTEIRO}`\
`Olá eu sou [Autoridade] e vou ajudar o [Avatar]`\
`Hoje vamos resolver o [Problema]`

`{REGRAS}`\
`> Siga o {ROTEIRO} acima e substitua os elementos entre [ ]`\
`Por aqueles listados em {RESUMO} acima`\
`> Mantenha o tom e ritmo, mas reescreva as palavras em {ROTEIRO} para que seja diferente do original, expandindo ou mudando conforme necessário.`\
`> Use analogias simples e hipérboles`

# Act commands que todo dev deveria saber

## Comandos de ação

- Qual a ideia de um comando de ação/act command?

  Você vai pedir pro ChatGPT se comportar como se fosse alguma outra coisa
  seja um agente, uma pessoa ou até um sistema e ele vai usar o poder computacional
  para agir da forma mais fiel ao que você propôs, com isso você pode desde
  simular um terminal de JavaScript até conversar com Einstein vai da sua
  criatividade e precisão

- Como é feito?

  Primeiramente você vai pedir para ele atuar como se fosse alguma coisa
  e como ele tem essa feature de memoria, tudo que você perguntar na
  sequência ele vai responder sem sair daquele papel, por exemplo:

  `Act as a JavaScript Console`

  e a partir desde ponto a IA vai agir como se fosse um terminal de JavaScript

## Elevando o nivel dos Act Commands
 
  Você pode adicionar regras como visto anteriormente aos comandos de ação
  para respostas mais certeiras e precisas, como por exemplo:

  `Comporte-se como se fosse um especialista de Front-End sênior que está me orientando
  a programar melhor`

  `{REGRAS}`\
  `> Sempre que eu te informar o que estou fazendo faça um checklist de boas práticas de
  front-end`\
  `> Sempre que eu te informar o que estou fazendo, ao final, envie uma sugestão de código`
