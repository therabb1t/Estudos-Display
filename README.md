# Estudos-Display
plano de aula extra

A Grid e o Flexbox são modelos de layout compostos por dimensões diferentes que organizam os elementos de uma interface, ambos influenciam a estrutura do site através do CSS.

### Grid
Grid Layout é um sistema bidimensional de organização de linhas, com conjuntos verticais e horizontais.
Dentro de um grid, respeitando a **configuração criada pelas suas linhas**, pode-se inserir elementos da marcação com funcionalidades diferentes, que susbstituem o uso do `float` e do `position`.

**Bi-dimensionalidade**
  A grid possui 2 tipos de dimensão, fixas ou flexíveis, fixas com o uso de pixels e flexiveis com o uso de porcentagem ou `fr`. 
  
  Fixa:
```.teste { display: grid; grid-template-columns: 200px 200px 200px; }```

Flexível:
```.teste { display: grid; grid-template-columns: 33% 33% 33%;}```

fr: 
```.teste { display: grid; grid-template-columns: 1fr 1fr 1fr; }```

**Funcionalidades da Grid**
- Posicionamento e Alinhamento
- Controle de Layers
- Grids Adicionais

**Propriedaedes da Grid**
Posicionamento dos rastros dos itens
`grid-template-comlumns`
`grid-template-rows`
`grid-auto`
`minmax`

**Linhas de Grid**
Posicionamento das linhas dos itens
`grid-column-start`
`grid-column-end`
`grid-row-start`
`grid-row-end`

**Separadores**
 `grid-column-gap`
 `grid-row-gap`






