# Estudos-Display
plano de aula extra

A Grid e o Flexbox são modelos de layout compostos por dimensões diferentes que organizam os elementos de uma interface, ambos influenciam a estrutura do site através do CSS e normalmente susbstituem o uso do `float` e do `position`.

>>> # Grid
Grid Layout é um sistema bidimensional de organização de linhas, com conjuntos verticais e horizontais.
Dentro de um grid, respeitando a **configuração criada pelas suas linhas**, pode-se inserir elementos da marcação com funcionalidades diferentes.

**Bi-dimensionalidade:**
  A grid possui 2 tipos de dimensão, fixas ou flexíveis, fixas com o uso de pixels e flexiveis com o uso de porcentagem ou `fr`. 
  
  Fixa:
```.teste { display: grid; grid-template-columns: 200px 200px 200px; }```

Flexível:
```.teste { display: grid; grid-template-columns: 33% 33% 33%;}```

fr: 
```.teste { display: grid; grid-template-columns: 1fr 1fr 1fr;}```

**Funcionalidades da Grid:**
- Posicionamento e Alinhamento
- Controle de Layers
- Grids Adicionais

**Propriedades da Grid:**
Posicionamento dos rastros dos itens

`grid-template-comlumns`

`grid-template-rows`

`grid-auto`

`minmax`

**Linhas de Grid:**
Posicionamento das linhas dos itens

```.teste { display: grid; [grid-column-start/ grid-column-end];}```

```.teste { display: grid; [grid-row-start/ grid-row-end];}```

**Separadores:**
```.teste { display: grid; [grid-column-gap/ grid-row-gap];}```

>>> # Flex
O Flexbox Layout é um sistema unidimensional e flexível de organização e alinhamento de uma interface, priorizando o conteúdo.
Ele não trabalha com o controle simultâneo das colunas e linhas, ou seja, ele lida com uma linha ou coluna de cada vez.

**Eixos:**

O Flex possui 2 eixos de operação, principais e transversais.

- Principal:
movido na direção principal, original.

- Transversal:
movido perpendicular a direção principal.

**Propriedades:** 

Flex-Direction:
ordem dos itens

```.teste{ display: flex; flex-direction:[row/ row-reverse/ column/ column-reverse];}```

Wrap:
posição e quebra dos itens em uma linha

```.teste{ display: flex; flex-wrap:[wrap/ no-wrap/ wrap-reverse];}```

Flow:
direction e wrap simplificados, abreviados

```.teste{ display: flex; flex-flow:[direction-wrap];}```

Justify-Content:
alinhamento dos itens

```.teste{ display: flex; justify-content:[flex-start/flex-end/center/space-between/space-around];}```

Align-Content:
aprimoramento do wrap, distribuição das linhas

```.teste{ display: flex; align-content:[stretch/flex-start/flex-end/center/space-between/space-around];}```

Align-Itens:
distribuição dos itens

```.teste{ display: flex; align-items: [stretch/flex-start/flex-end/center/baseline];}```

Align-Self:
sobrescreve o align-itens

```.teste{ display: flex; align-self: [auto/stretch/flex-start/flex-end/center/baseline];}```

**Propriedades de Valores:**
proporção do tamanho de um item

```.teste {flex-grow:[número];}```

```.teste {flex-shrink:[número];}```

```.teste {flex-basis:[número];}```

```.teste {order:[número];}```





refs:

https://www.geeksforgeeks.org/comparison-between-css-grid-css-flexbox/

https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_grid_layout/Basic_concepts_of_grid_layout#c%C3%A9lulas_do_grid

https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_flexible_box_layout/Basic_concepts_of_flexbox

https://www.devmedia.com.br/css3-flexbox-funcionamento-e-propriedades/29532#direction

https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout/Relationship_of_flexbox_to_other_layout_methods
