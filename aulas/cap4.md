# **4. Propriedades dos Itens Flexíveis**
Essas propriedades só terão funcionalidade caso o item seja flexível.

## **4.1 `order` – Definição de ordem de exibição**
O `order` especifica a posição dos itens no flex. O usuário utiliza o `order` no item que quer mudar a ordem. O primeiro elemento é o `0`.

### **Exemplo de Código:**
```css
.item {
  order: 2; /* Move o elemento para a terceira posição */
}
```

## **4.2 `flex-grow` – Crescimento proporcional dos itens**
Define quanto um item flex crescerá de acordo com o container.

### **Exemplo de Código:**
```css
.item {
  flex-grow: 1; /* Permite que o item cresça */
}
```

## **4.3 `flex-shrink` – Redução proporcional dos itens**
Define quanto um item flex diminuirá para se ajustar ao container.

### **Exemplo de Código:**
```css
.item {
  flex-shrink: 2; /* Faz o item diminuir o dobro de outros */
}
```

## **4.4 `flex-basis` – Tamanho inicial do item**
Essa propriedade define o tamanho inicial do item antes que o `flex-grow` ou `flex-shrink` atuem sobre ele.

### **Exemplo de Código:**
```css
.item {
  flex-basis: 100px; /* Define o tamanho inicial do item */
}
```

## **4.5 `flex` – Atalho para `flex-grow`, `flex-shrink` e `flex-basis`**
É um atalho para `flex-grow`, `flex-shrink` e `flex-basis`, utilizado para simplificar a escrita do código.

### **Exemplo de Código:**
```css
.item {
  flex: 1 1 100px; /* Cresce, encolhe e começa com 100px */
}
```

## **4.6 `align-self` – Alinhamento individual dos itens**
Alinha os itens individualmente dentro do container, sobrescrevendo o `align-items`.

### **Exemplo de Código:**
```css
.item {
  align-self: center; /* Alinha este item ao centro */
}
```

---

# **Exercícios do Capítulo**

## **Questão Dissertativa**

1. Explique a diferença entre `flex-grow`, `flex-shrink` e `flex-basis`.

## **Questão de Múltipla Escolha**

2. O que acontece quando aplicamos `align-self: center;` em um item flex dentro de um container com `align-items: flex-start;`?
   - (A) O item permanecerá alinhado ao início do container.
   - (B) O item será centralizado verticalmente dentro do container.
   - (C) O item será deslocado para o final do container.
   - (D) Nada muda, pois `align-self` precisa ser aplicado ao container.
