# **1. Introdução ao CSS Flexbox**

## **1.1 O que é Flexbox?**

Foi projetado para ser um modelo de layout unidimensional e também para organizar especialmente os elementos em uma interface, além de possuir capacidades de alinhamento.

## **1.2 Quando usar Flexbox?**

Usa-se flexbox quando queremos alinhar elementos dentro de um container. Um exemplo comum é centralizar uma imagem dentro de um container.

## **Exemplo Prático**

```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 200px;
}
```

Isso centraliza os itens horizontal e verticalmente dentro do container.

## **1.3 Diferença entre Flexbox e outras técnicas de layout (Float, Grid, Inline-Block)**

O flexbox é utilizado para layouts unidimensionais, já o grid é feito para layouts bidimensionais e complexos. O flexbox pode trabalhar em linhas ou colunas ao mesmo tempo, entretanto os grids podem trabalhar em ambos.

### **Tabela Comparativa**

| Flexbox           | Grid               |
| ----------------- | ------------------ |
| Unidimensional    | Bidimensional      |
| Linhas ou colunas | Linhas e colunas   |
| Flexibilidade     | Projetos complexos |

## **Exemplo Prático**

```css
.flex-container {
  display: flex;
}

.grid-container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
}
```

Isso demonstra como definir um container Flexbox e um Grid para organização de elementos.

# **Exercícios do Capítulo**

## **Questão Dissertativa**

1. Quais são os benefícios do Flexbox?

## **Questão de Múltipla Escolha**

2. Qual das opções abaixo representa um caso ideal para o uso de Flexbox?
   - (A) Criar um layout com múltiplas colunas e linhas organizadas de forma fixa.
   - (B) Criar uma galeria de imagens onde cada item deve ter tamanhos flexíveis e alinhamento dinâmico.
   - (C) Posicionar um banner de publicidade fixo na lateral de um site.
   - (D) Criar uma grade de produtos com um espaçamento fixo e alinhamento uniforme.

