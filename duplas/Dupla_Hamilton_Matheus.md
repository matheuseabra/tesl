# Dupla

- Hamilton Cavalcante (hamiltoncavalcante@gmail.com)
- Matheus Seabra (matheusvieiracoelho@gmail.com)

### Links para atividades:

## Atividade 01:
- 

## Atividade 02: 
- 

## Atividade 03

1 - Obrigatória
- commit: uma operação que descreve certa mudança/incremento/exclusão de código
- push: Envia mudanças locais para o reposiório origem
- pull: puxa mudanças localmente do repsotório de origem
- checkout: alterna entre branches
- log: exibe uma série de informações sobre a mudança
- shortlog: exibe um log mais curto sobre as mudanças

2 - git shortlog -n -e 

## Atividade 04

1. Selecione e identifique em um determinado projeto de software livre se a página inicial ou alguma página logo em seguida tem (ou não) links para instalação, documentação, documentação traduzida, e como contribuir. Coloque o projeto avaliado e os links encontrados (ou não).

Projeto: Cypress.io
Função do projeto: JavaScript End to End Testing
Link do repositório: https://github.com/cypress-io/cypress
Link para documentação: https://docs.cypress.io
Link de como contribuir: https://github.com/cypress-io/cypress/blob/develop/CONTRIBUTING.md
Template para abrir Pull Request: https://github.com/cypress-io/cypress/blob/develop/PULL_REQUEST_TEMPLATE.md
Código de conduta: https://github.com/cypress-io/cypress/blob/develop/CODE_OF_CONDUCT.md
Link para o FAQ: https://docs.cypress.io/faq/questions/using-cypress-faq.html
Link para Traduções: não possui link

2. Revise uma página de um projeto de software livre e sumarize os problemas encontrados (o que falta para ela ser mais informativa)

Projeto: Mongoose
Link para o repositório: https://github.com/Automattic/mongoose
Link para documentação: 
Problemas encontrados:
- Falta página de traduções
Sugestão de como melhorar:
- Adicionar página de tradução
- Adicionar página de código de conduta
- Adicionar template de Pull request
- Adicionar template para issues 


3. Teste a documentação (por exemplo, siga as instruções de instalação) e sumarize os problemas encontrados.

Documentação: https://docs.cypress.io

Passos para instalação: 

passo 1: Instala a blibioteca globalmente e como dependência de desenvolvimento
```npm install cypress -g --save-dev``` 

passo 2: Abre o terminal interativo para executar os testes 
```npm run cypress open```

Problema encontrado: o Cypress ainda não possui uma maneira de simular cliques os outros eventos do navegador de forma condicional. Isso acontece pois o DOM nas aplicações usando JavaScript de hoje se torna incrivelmente instável. Portanto, o Cypress tem dificuldade em saber quais elementos HTML estão em telas e os que não estão, fazendo com que alguns testes podem ser considerados "frágeis", ou seja, não consistentes, e podem falhar por razões aleatórias.


