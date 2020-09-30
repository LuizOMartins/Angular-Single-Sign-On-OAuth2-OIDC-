-	O SSO é uma solução tecnológica que permite que esses aplicativos usem a mesma senha para todos os acessos de forma segura e  transparente.

# Como funciona o SSO?

1 -O site primeiro verifica se você já foi autenticado pela solução SSO e, nesse caso, ele fornece acesso ao site.
2 - Se ainda não tiver feito isso, você será direcionado à solução SSO para fazer login.
3 - Você insere o único nome de usuário / senha que usa para acesso corporativo.
4 - A solução SSO solicita autenticação do provedor de identidade ou sistema de autenticação que sua empresa usa. Ele verifica sua identidade e notifica a solução SSO.
5 - A solução SSO passa os dados de autenticação para o site e retorna você a esse site.
6 - Após o login, o site passa os dados de verificação de autenticação com você conforme você se move pelo site para verificar se você está autenticado sempre que acessar uma nova página.
No SSO, os dados de verificação de autenticação assumem a forma de tokens.


## Aouth2:

* Roles (papéis)
* OAuth 2 foi construído em cima de 4 papéis, sendo:

-	Resource Owner – pessoa ou entidade que concede o acesso aos seus dados. Também chamado de dono do recurso.
-	Client – é a aplicação que interage com o Resource Owner, como por exemplo o browser, falando no caso de uma aplicação web.
- Resource Server – a API que está exposta na internet e precisa de proteção dos dados. Para conseguir acesso ao seu conteúdo é necessário um token que é emitido pelo authorization server.
- Authorization Server – responsável por autenticar o usuário e emitir os tokens de acesso. É ele que possui as informações do resource owner (o usuário), autentica e interage com o usuário após a identificação do client.

##Como funciona?

![Fluxo](https://raw.githubusercontent.com/LuizOMartins/Angular-Single-Sign-On-OAuth2-OIDC-/master/FLUXO-IMG.png )



_______________________________________________________________________________

# SSO (Single-Sign-On) Angular App
A Basic level implementation example for Single Sgn-On (SSO) in Angular 8 using OAuth2 and Open ID Connect(OIDC).
Here is the step-by-step [youtube video tutorial](https://youtu.be/AcuzemsJfxA) of this application.

![Angular Single Sign-On youtube tutorial](https://raw.githubusercontent.com/shaheershukur/Angular-Single-Sign-On-OAuth2-OIDC-/master/angular-single-sign-on-oauth2-oidc-shaheershukur.jpg )

# Made with Angular 
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.0.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).




____________________________________________________________________


Refências:

- https://www.onelogin.com/learn/how-single-sign-on-works

- https://www.treinaweb.com.br/