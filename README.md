# AngularDashboard

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.0.6.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## Estrutura

Core

Tudo que é essencial para o funcionamento da aplicação.

Models, nessa pasta estão os modelos os quais criou para sua aplicação.

Components, aqui estão os componentes universais da aplicação. A navbar ou o footer que criou são bons exemplos.

Guards, é onde você irá por os guardas de rota que criou, como por exemplo aquele para proteger rotas que o usuário estar autenticado é um pré-requisito.

Interceptors, é a pasta que conterá nossos interceptadores de requisições, um exemplo mais que excelente é um interceptor cujo sua responsabilidade é injetar o token obtido no header da requisição.

Layouts, pasta que armazena os layouts pré-definidos criados da aplicação.

Translations, armazena as traduções utilizadas na internacionalização.

Configs, pasta onde fica alguns arquivos de configuração.

Overrides, é a pasta que tem os arquivos que utilizamos para sobrescrever uma parte terceira. Um exemplo é um arquivo responsável por sobrescrever uma classe do Bootstrap.

Variables.scss, é um arquivo com algumas variáveis CSS que podem ser necessárias.

Theme.scss, é um arquivo de tema. Muito comum para customizar uma UI que está utilizando como Bootstrap, Angular Material, PrimeNG etc.

Modules

Pasta que contém todos os módulos que agregam valor ao sistema, ou seja, as entregas. Modules são as características do sistema.

Shared

Aqui fica tudo que é compartilhado e reutilizado em toda aplicação, não tem segredo.

As pastas filhas são apenas para agrupar por tipo de conteúdo — pipes com pipes, components com components e assim por diante.
