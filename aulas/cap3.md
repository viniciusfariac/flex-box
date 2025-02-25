# **3. Propriedades do Contêiner Flexível**

## **3.1 `flex-direction` – Direção dos elementos**
`flex-direction` é utilizado nos elementos pais (flex-containers) para definir a direção de seus elementos filhos (flex-items):

- `row` (valor padrão): Deixa os elementos filhos na mesma linha.
- `row-reverse`: Deixa os elementos filhos na mesma linha, porém invertidos.
- `column`: Deixa os elementos filhos em coluna.
- `column-reverse`: Deixa os elementos filhos em coluna, porém invertida.

### **Exemplo de Código:**

```css
.flex-container {
  display: flex;
  flex-direction: row;
}
```

## **3.2 `flex-wrap` – Quebra de linha dos itens**
`flex-wrap` é utilizado para quebrar linhas dos elementos filhos, usado nos elementos pais:

- `nowrap` (valor padrão): Não permite a quebra de linha.
- `wrap`: Quebra a linha, caso seja necessário.
- `wrap-reverse`: Quebra a linha, caso seja necessário, porém invertida.

### **Exemplo de Código:**

```css
.flex-container {
  display: flex;
  flex-wrap: wrap;
}
```

## **3.3 `flex-flow` – Atalho para `flex-direction` e `flex-wrap`**
O `flex-flow` é uma junção do `flex-direction` com o `flex-wrap`, sendo o primeiro argumento `flex-direction` e o segundo `flex-wrap`.

### **Exemplo de Código:**

```css
.flex-container {
  display: flex;
  flex-flow: row wrap;
}
```

## **3.4 `justify-content` – Alinhamento horizontal dos itens**
É o alinhamento horizontal (eixo X) dos elementos:

```css
/* Positional alignment */
justify-content: center; /* Alinhamento ao centro */
justify-content: start; /* Alinhamento no começo */
justify-content: end; /* Alinhamento no final */
justify-content: flex-start; /* Alinhamento flexível no começo */
justify-content: flex-end; /* Alinhamento flexível no final */

/* Distributed alignment */
justify-content: space-between; /* Espaço uniforme entre os itens */
justify-content: space-around; /* Espaço uniforme ao redor dos itens */
justify-content: space-evenly; /* Espaço uniforme entre os itens e as bordas */
```

### **Exemplo de Código:**

```css
.flex-container {
  display: flex;
  justify-content: space-between;
}
```

## **3.5 `align-items` – Alinhamento vertical dos itens**
É o alinhamento vertical (eixo Y) dos elementos:

```css
/* Basic keywords */
align-items: normal; /* Alinhamento normal */
align-items: stretch; /* Os itens se ajustam ao container */

/* Positional alignment */
align-items: center; /* Alinhamento ao centro */
align-items: start; /* Alinhamento no começo */
align-items: end; /* Alinhamento no final */
align-items: flex-start; /* Alinhamento flexível no início */
align-items: flex-end; /* Alinhamento flexível no final */
```

### **Exemplo de Código:**

```css
.flex-container {
  display: flex;
  align-items: center;
}
```

## **3.6 `align-content` – Alinhamento em múltiplas linhas**
Alinha elementos em múltiplas linhas quando o `flex-wrap` está ativado.

### **Exemplo de Código:**

```css
.flex-container {
  display: flex;
  flex-wrap: wrap;
  align-content: space-between;
}
```

---

# **Exercícios do Capítulo**

## **Questão Dissertativa**

1. Explique a diferença entre `justify-content` e `align-items`.

## **Questão de Múltipla Escolha**

2. O que acontece quando aplicamos `justify-content: space-between;` em um container flex?
   - (A) Os itens são distribuídos igualmente dentro do container, com espaços iguais entre si e as bordas.
   - (B) Os itens são alinhados ao centro do container.
   - (C) Os itens são distribuídos igualmente, deixando espaços apenas entre eles, sem tocar nas bordas.
   - (D) Nada muda, pois `justify-content` precisa ser usado com `flex-wrap`.
