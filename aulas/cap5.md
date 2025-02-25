# **5. Técnicas e Padrões de Layout com Flexbox**

## **5.1 Criando um layout de coluna responsivo**
Para criar um layout de coluna, primeiramente o usuário precisa entender que a direção será em coluna, após isso o próprio usuário decidirá como serão os espaçamentos (`justify-content`, `align-items`).

## **5.2 Criando um layout de linha responsivo**
Para criar um layout de linha responsivo, primeiramente o usuário precisa entender que a direção será `row` (padrão), após isso o próprio usuário decidirá como serão os espaçamentos (`justify-content`, `align-items`).

## **5.3 Centralizando elementos com Flexbox**
Para centralizar os elementos com Flexbox, pode-se utilizar no container a propriedade `display` com valor `flex`, logo em seguida utilizar `align-items` e `justify-content` com o valor `center`.

## **5.4 Criando um menu de navegação flexível**
Coloca-se um container (`header`) que conterá uma `img` e uma `ul`. No container, aplica-se `display: flex`, `justify-content: space-around` e `align-items: center`. Na `ul`, utiliza-se `display: flex`, `justify-content: center` e `align-items: center`.

## **5.5 Criando um grid de cards com Flexbox**
Utiliza-se `display: flex` no container, seguido de `justify-content: center` e `flex-wrap: wrap`. Isso permite que os cards quebrem as linhas conforme necessário.

