# CLI-em-NodeJS

Desenvolvendo ferramentas de linha de comando em NodeJS

## Objetivos

- Entender a necessidade das CLIs (Command Line Interface) 
- Criar CLI em nodejs para pesquisar arquivo em diretório
- Instalar a ferramenta localmente para poder testar
- publicar ferramenta no NPM

## Requisitos Básicos 

- Javascript
- Familiaridade com o terminal
- Node e npm instalados na máquina

## Observações
- CLI: Ferramenta que disponibiliza uma interface de linha de comando para para execução de tarefas via terminal;
- Normalmente criados em Shell Script
- Ele automatiza uma tarefa através de um arquivo executável
- Para instalar localmente e poder usar o comando no terminal, use o comando: npm link. O comando search-files vai estar disponível no terminal. Você pode usar o comando passando o nome do arquivo que deseja procurar no diretório atual: search-files .json. Neste exemplo, listaria todos os arquivos com a extensão .json.