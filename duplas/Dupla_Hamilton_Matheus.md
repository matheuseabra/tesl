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

## Atividade 05

1. Justifique o que acontece se um projeto de software não tiver nenhuma licença definida.

R = Se um projeto não possui licença, então não é considerado open source. Se não tiver uma licença que conceda ao usuário do software direitos específicos além dos direitos concedidos a ele/ela pela lei de direitos autorais (que são praticamente nenhum), então ela não é de código aberto. Em particular, não seria possível ter permissão para copiá-lo, modificá-lo, distribuí-lo, nem baixá-lo, etc. Dependendo da jurisdição, pode-se nem ter permissão para executá-lo, pois a execução envolve a cópia do disco para a RAM; a maioria das jurisdições, felizmente, se afastou dessa interpretação, mas ainda pode haver algumas que não foram.

Nota do GitHub sobre o assunto: https://help.github.com/en/articles/licensing-a-repository#what-happens-if-i-dont-choose-a-license

>You're under no obligation to choose a license. It's your right not to include one with your code or project, but please be aware of the implications. Generally speaking, the absence of a license means that the default copyright laws apply. This means that you retain all rights to your source code and that nobody else may reproduce, distribute, or create derivative works from your work. This might not be what you intend.

>Even if this is what you intend, if you publish your source code in a public repository on GitHub, you have accepted the Terms of Service which do allow other GitHub users some rights. Specifically, you allow others to view and fork your repository.

>If you want to share your work with others, we strongly encourage you to include an open source license.

2. Procure um projeto sem licença de software e adicione uma

Projeto: https://github.com/matheuseabra/js-dev-tools
Licença: GNU General Public License v3.0
Link da licança no repositório: https://github.com/matheuseabra/js-dev-tools/blob/master/License.md

3. Procure por projetos de software que utilize uma licença que não deveria ser empregada em projetos de software.

Projeto: https://www.freertos.org/

Como exemplo, o sistema operacional em tempo real FreeRTOS é licenciado sob a Licença Open Source do FreeRTOS que é baseada em uma GNU GPL modificada, a modificação assumindo a forma de uma exceção. A GNU GPL é aprovada pela Open Source Initiative, mas não pela FreeRTOS Open Source License.



