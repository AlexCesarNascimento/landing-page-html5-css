# Landing page com os melhores padrões de HTML e CSS

Esta página foi produzida exclusivamente com HTML e CSS e você pode acessa-la [aqui!](https://glistening-moonbeam-1da5d2.netlify.app/#)

- Deploy: 
  - https://app.netlify.com/
- Imagens: 
  - Background: https://www.svgbackgrounds.com
  - Ilustrações: https://undraw.co/illustrations
  - Galeria: https://source.unsplash.com/random/360x360
# Commits

```
<Tipos>(<Escopo>): <curta descrição>
  │       │             │
  │       │             └─⫸ Resumo no tempo presente. Não capitalizado. Sem ponto final.
  │       │
  │       └─⫸ Escopo de commit:  Opcional, pode ser qualquer coisa que especifique o escopo da alteração de confirmação.
  |                               Por exemplo $location|$browser|$compile|$rootScope|ngHref|ngClick|ngView, etc.
  |                               No desenvolvimento de aplicativos, o escopo pode ser uma página, um módulo ou um componente.
  │
  └─⫸ Tipos de commit: feat|fix|docs|style|refactor|test|chore|perf|ci|build|temp
```

# Atalhos - Emmet Abbreviation
[documentação](https://docs.emmet.io/cheat-sheet/)

> Multiplicando valor do texto com variavel

**div>div{item $}*3 **

```html
<div>
  <div>item 1</div>
  <div>item 2</div>
  <div>item 3</div>
</div>
```


> Multiplicando a classe com variavel

**ul>li.item$@* 3 **

```html
<ul>
  <li class="item1"></li>
  <li class="item2"></li>
  <li class="item3"></li>
</ul>
```


> Adicionado um irmão para a div pai ^

**div.avo>div.pai>div.filho^div.tio**

```html
<div class="avo">
  <div class="pai">
    <div class="filho"></div>
  </div>
  <div class="tio"></div>
</div>
```
