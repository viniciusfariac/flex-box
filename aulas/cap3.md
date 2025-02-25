# **3. Propriedades do Contêiner Flexível**

## **3.1 `flex-direction` – Direção dos elementos**
`flex-direction` é utilizado nos elementos pais (flex-containers) para definir a direção de seus elementos filhos (flex-items):

- `row` (valor padrão): Deixa os elementos filhos na mesma linha.
- `row-reverse`: Deixa os elementos filhos na mesma linha, porém invertidos.
- `column`: Deixa os elementos filhos em coluna.
- `column-reverse`: Deixa os elementos filhos em coluna, porém invertida.

## **3.2 `flex-wrap` – Quebra de linha dos itens**
`flex-wrap` é utilizado para quebrar linhas dos elementos filhos, usado nos elementos pais:

- `nowrap` (valor padrão): Não permite a quebra de linha.
- `wrap`: Quebra a linha, caso seja necessário.
- `wrap-reverse`: Quebra a linha, caso seja necessário, porém invertida.

## **3.3 `flex-flow` – Atalho para `flex-direction` e `flex-wrap`**
O `flex-flow` é uma junção do `flex-direction` com o `flex-wrap`, sendo o primeiro argumento `flex-direction` e o segundo `flex-wrap`.

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

## **3.6 `align-content` – Alinhamento em múltiplas linhas**
Alinha elementos em múltiplas linhas quando o `flex-wrap` está ativado.

---