# **4. Propriedades dos Itens Flexíveis**
Essas propriedades só terão funcionalidade caso o item seja flexível.

## **4.1 `order` – Definição de ordem de exibição**
O `order` especifica a posição dos itens no flex. O usuário utiliza o `order` no item que quer mudar a ordem. O primeiro elemento é o `0`.

Exemplo:
```css
.item {
  order: 2; /* Move o elemento para a terceira posição */
}
```

## **4.2 `flex-grow` – Crescimento proporcional dos itens**
Define quanto um item flex crescerá de acordo com o container.

```css
.item {
  flex-grow: 1; /* Permite que o item cresça */
}
```

## **4.3 `flex-shrink` – Redução proporcional dos itens**
Define quanto um item flex diminuirá para se ajustar ao container.

```css
.item {
  flex-shrink: 2; /* Faz o item diminuir o dobro de outros */
}
```

## **4.4 `flex-basis` – Tamanho inicial do item**
Essa propriedade define o tamanho inicial do item antes que o `flex-grow` ou `flex-shrink` atuem sobre ele.

```css
.item {
  flex-basis: 100px; /* Define o tamanho inicial do item */
}
```

## **4.5 `flex` – Atalho para `flex-grow`, `flex-shrink` e `flex-basis`**
É um atalho para `flex-grow`, `flex-shrink` e `flex-basis`, utilizado para simplificar a escrita do código.

```css
.item {
  flex: 1 1 100px; /* Cresce, encolhe e começa com 100px */
}
```

## **4.6 `align-self` – Alinhamento individual dos itens**
Alinha os itens individualmente dentro do container, sobrescrevendo o `align-items`.

```css
.item {
  align-self: center; /* Alinha este item ao centro */
}
```

---