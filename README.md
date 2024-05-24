
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