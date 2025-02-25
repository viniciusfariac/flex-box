#### **1. Introdução ao CSS Flexbox**

##### **1.1 O que é Flexbox?**
Foi projetado para ser um modelo de layout unidimensional e também para organizar especialmente os elementos em uma interface, além de possuir capacidades de alinhamento.

##### **1.2 Quando usar Flexbox?**
Usa-se flexbox quando queremos alinhar um bloco de código. Centralizar uma imagem dentro de um container, por exemplo.

##### **1.3 Diferença entre Flexbox e outras técnicas de layout (Float, Grid, Inline-Block)**
O flexbox é utilizado para layouts unidimensionais, já o grid é feito para layouts bidimensionais e complexos. O flexbox pode trabalhar em linhas ou colunas ao mesmo tempo, entretanto os grids podem trabalhar em ambos.

| Flexbox | Grid |
|---------|------|
| Unidimensional | Bidimensional |
| Linhas ou colunas | Linhas e colunas |
| Flexibilidade | Projetos complexos |

#### **2. Conceitos Fundamentais**

##### **2.1 O Modelo de Caixa Flexível**
O modelo de caixa flexível, ou flexbox, é um modelo que organiza itens em linhas ou colunas, mas não ambos. O flexbox facilita o design de uma estrutura de layout sem ser preciso a utilização de float.

##### **2.2 Elemento Pai (Flex Container) vs. Elementos Filhos (Flex Items)**
O elemento pai (Flex Container) é o elemento que manda em seus filhos, ele é o elemento chave que o usuário precisa colocar o flex. O elemento filho é o elemento que obedece as ordens do pai. Se o pai pedir para ele se organizar de uma forma, ele se organizará.

**Exemplo de Código HTML:**
```html
<div class="flex-pai">
  <div class="flex-filho">One</div>
  <div class="flex-filho">Two</div>
  <div class="flex-filho">Three</div>
</div>
```

**Exemplo de Código CSS:**
```css
.flex-pai {
  display: flex;
  flex-direction: center;
}
```

##### **2.3 Propriedade `display: flex` e seus efeitos**
A propriedade `display: flex` é usada no elemento pai. Por padrão, todos os elementos filhos ficarão em uma linha, pois seu `flex-direction` inicia-se como `row`. Se você quiser os elementos em colunas, precisa utilizar `flex-direction: column`.

O principal efeito do `display: flex` é deixar os elementos filhos flexíveis, ou seja, adaptados às ordens que o elemento pai tiver.

---