<!--

WARNING!! DON'T EDIT THE FILE README.md on the root of the project, that one is a GENERATED FILE!

You should just edit the source file at src/README.md - the one which stars with ## @@title

-->

## @@title

# RAICHU

@@author @ [ReclameAQUI](http://www.reclameaqui.com.br)

*@@email*

@@date

---

## Agenda

- Estrat&eacute;gias de Arquitetura para entrega de p&aacute;ginas HTTP
  - Ass&iacute;ncrona N&atilde;o Bloqueante
  - Como &eacute; a Arquitetura Tradicional
- Integra&ccedil;&atilde;o com o Backend
- Escolha do framework Javascript
- Load de javascript
- Estrutura de diret&oacute;rios
- Premissas
- Refer&ecirc;ncias
- Obrigado

---

##  Estrat&eacute;gias de Arquitetura para entrega de p&aacute;ginas HTTP

*abaixo*

----

## Ass&iacute;ncrona N&atilde;o Bloqueante

<img src="img/slide_web_async.png" class="slide_img" style="border: none;" />

----

## Como &eacute; a Tradicional

<img src="img/slide_web_tradicional.png" class="slide_img" style="border: none;" />

---

## Integra&ccedil;&atilde;o com o Backend.

<img src="img/slide_consumo_de_api.png" class="slide_img" style="border: none;" />

---

## Escolha de framework Javascript.

<img src="img/slide_js_framework.png" class="slide_img" style="border: none;" />

---

## Load de Javascript

### CommonJS

- permite a escrita de javascript (frontend *AngularJS*) similar a escrita de javascript de (backend *NodeJS*)
- Para isso se usa a ferramenta *Browserify*

### AMD (Asynchronous Module Definition)

- Possui vantagens em sistema SPA (single page application) com muitas p&aacute;ginas, &eacute; o caso do Hugme.
- Para isso se usa a ferramenta *RequireJS*.

---

## Estrutura de diret&oacute;rios

- /client
  - /src
    - /app
    - /favicon
    - /img
    - /json
    - /sass (css)
  - /dist
    - /0.0.1
    - /0.0.2

*continua abaixo*

----

- /views
  - /home
    - app-recentes
    - capa
    - espalhe-sua-historia
    - especiais
    - melhores-empresas
    - tendencias
  - error
  - layout
  - index
  - sidenav

*continua abaixo*

----

- /bin
  - www
- /routes
- Gruntfile.js
- app.js
- package.json
- README.md
- bower.json

---

## Premissas

- As APIs precisam estar em padr&atilde;o RESTful, em sua perfeita sem&acirc;ntica e autenticadas (quando necess&aacute;rio) por token.

---

## Refer&ecirc;ncias

1. [ExpressJS API Reference](http://expressjs.com/4x/api.html)
2. [AngularJS vs. Backbone.js vs. Ember.js](https://www.airpair.com/js/javascript-framework-comparison)


---

## Obrigado

# FIM

