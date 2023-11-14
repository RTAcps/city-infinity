# city-infinity

ToDo List build in Angular

## Sumário

- [Desenvolvimento, por onde começar](#desenvolvimento-por-onde-começar)
- [Servidor de desenvolvimento](#servidor-de-desenvolvimento)
- [Dependências](#dependencias)
- [Deploy](#deploy)
- [Estrutura](#estrutura)
- [Estrutura de código](#estrutura-de-codigo)
- [Build](#build)
- [Executando testes unitários](#testes)
- [Executando lint](#lint)
- [Executando testes de ponta-a-ponta](#testes-de-ponta-a-ponta)
- [Mais ajuda?](#ajuda)

## Desenvolvimento, por onde começar

-- (Passos para execução do projeto, build, execução e relatório dos testes.)
Exemplo:

```bash
# Instale as dependências
npm install
npm i

# Rodar a aplicação
ng serve
ng s

# Executar os testes
ng test

# Executar os testes e gerar relatório de cobertura de código
ng test --code-coverage

# Executar o mesmo comando de teste executado pelo pipeline de CI
npm run test:ci

# Executar lint
ng lint
nodemon --watch src -e ts,html,scss --exec "ng lint"

```

## Servidor de desenvolvimento

Execute `ng serve` para um servidor dev. Navegue para `http://localhost:4200/`. A aplicação será automaticamente recarregada quando você fizer qualquer alteração nos arquivos fontes.

## Dependências

-- (Informações sobre dependências, como APIs).

## Deploy

-- (Url da da aplicação publicada)

## Estrutura

Este projeto foi gerado com [Angular CLI](https://github.com/angular/angular-cli) version 17.0.0.

## Estrutura de código

Execute `ng generate component component-name` ou resumidamente `ng g c component-name` para gerar um novo componente.
Você também pode usar:

- `ng g service` auxilia a separar do componente parte das informações importantes e modo de obtenção, lógica de negócios e dados de requisições ao servidor;
- `ng g module` ajuda a organizar e modularizar a aplicação;
- `ng g class` cria uma nova definição de classe genérica no projeto especificado;
- `ng g pipe` que ajuda a transformar dados que estão em um formato para outro, verifique se o pipe desejado já não existe nativamente no Angular;
- `ng g directive` cria uma nova diretiva, que adiciona comportamentos nos elementos do template;
- `ng g config` gera um arquivo de configuração no projeto fornecido;
- `ng g enum` facilita o manuseio de grupos de constantes nomeadas;
- `ng g guard` gera uma nova definição genérica de protetor de rota no projeto;
- `ng g interface` cria estruturas responsáveis por definirem tipos customizados para os dado;
- `ng g environments` gera e configura arquivos de ambiente para um projeto;
- `ng g web-worker` permite executar cálculos com uso intensivo de CPU em um thread em segundo plano, liberando o thread principal para atualizar a interface do usuário;
- `ng g service-worker` é um script que é executado no navegador da Web e gerencia o cache de um aplicativo;
- `ng g app-shell` uma maneira de renderizar uma parte do aplicativo usando uma rota em tempo de compilação.

## Build

Execute `ng build` para montar o projeto. Os artefatos de construção serão armazenados no diretório `dist/`.

## Executando testes unitários

Execute `ng test` para os testes de unidade via [Karma](https://karma-runner.github.io).

## Executando lint

Execute `ng lint` que é a ferramenta de análise de código, usada para sinalizar erros de programação, erros estilísticos, bugs e construções suspeitas que prejudicam ou causam o baixo desempenho ao código da aplicação. Você pode instalar o nodemon `npm i -g nodemon` (instalar uma vez) e ao executar `nodemon --watch src -e ts,html,scss --exec "ng lint"` verifica o lint automaticamente a cada alteração.

## Executando testes de ponta-a-ponta

Execute `ng e2e` para os testes ponta-a-ponta através de uma plataforma de sua escolha. Para usar este comando, você precisa primeiro adicionar um pacote que implemente recursos de teste ponta-a-ponta.

## Mais ajuda?

Para obter mais ajuda sobre o Angular CLI, use `ng help` ou confira a página [Visão geral do Angular CLI e referência de comandos](https://angular.dev/cli).
