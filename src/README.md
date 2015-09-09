<!--

WARNING!! DON'T EDIT THE FILE README.md on the root of the project, that one is a GENERATED FILE!

You should just edit the source file at src/README.md - the one which stars with ## @@title

-->

## @@title

<img src="img/AngularJS-large.png" class="slide_img" style="border: none; background-color: transparent; box-shadow: none;" />

&nbsp;
&nbsp;

@@author

*@@email*

@@date

---

## Agenda

- Escolha do framework
- Exemplo simplificado (ng directives)
- AngularJS e seu two-ways data-binding
- Trabalhando com Controllers
- Trabalhando com Servi&ccedil;os
- Trabalhando com Filtros nativos

---

## Escolha do framework

<img src="img/slide_js_framework.png" class="slide_img" style="border: none;" />

---

## Exemplo simplificado
#### (ng directives)

```
<div ng-app ng-init="show = 'hello'">
    <div ng-show="show == 'hello'">
        <h1>Hello World</h1>
    </div>
    <div ng-show="show == 'song'">
        <h1>I saw you say let say let saw...</h1>
        <p>I feel good because you put your but on me</p>
    </div>
    <button type="button" ng-click="show = 'hello'"
        ng-class="{'active': show == 'hello'}">Show Hello</button>
    <button type="button" ng-click="show = 'song'"
        ng-class="{'active': show == 'song'}">Sing me a song</button>
</div>
```

[JSFiddle]([https://jsfiddle.net/5a3on5xg)

---

## AngularJS e seu two-ways data-binding

No Angular tudo oque &eacute; declarado como ***$scope*** no controller fica dispon&iacute;vel para a ***view em html*** e para as ***ng-directives***, tornando assim f&aacute;cil de manipular e ser&atilde;o exibidas no template atrav&eacute;s dos mustaches ***{{}}***

Assim uma altera&ccedil;&atilde;o de vari&aacute;vel no controller reflete automaticamente na view e vice-versa.

---

## Trabalhando com Controllers

```

```

---

## Refer&ecirc;ncias

1. [AngularJS vs. Backbone.js vs. Ember.js](https://www.airpair.com/js/javascript-framework-comparison)
2. [Creating a CRUD App in Minutes with Angular's $resource](http://www.sitepoint.com/creating-crud-app-minutes-angulars-resource/)

---

# FIM



