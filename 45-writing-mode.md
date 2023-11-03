# ✒ Propriedade `writing-mode` em CSS

## ⁉ O que é a Propriedade `writing-mode`?
- A propriedade `writing-mode` em CSS é usada para controlar a direção da escrita e o layout do texto em elementos HTML.

## 💰 Valores da Propriedade `writing-mode`
- A propriedade `writing-mode` aceita diversos valores, incluindo:
  - `horizontal-tb`: Valor padrão, com texto da esquerda para a direita e de cima para baixo, como na maioria dos idiomas ocidentais.
  - `vertical-rl`: Texto de cima para baixo e da direita para a esquerda, como em idiomas escritos verticalmente, como o japonês.
  - `vertical-lr`: Texto de cima para baixo e da esquerda para a direita, como em alguns estilos de escrita chinesa.
  - `sideways-rl`: Texto disposto na horizontal, da direita para a esquerda.
  - `sideways-lr`: Texto disposto na horizontal, da esquerda para a direita.

## ✒ Uso Comum da Propriedade `writing-mode`
- A propriedade `writing-mode` é frequentemente usada para controlar a direção da escrita em idiomas que não seguem a escrita ocidental padrão da esquerda para a direita.

## 👩‍🏫 Exemplo de Uso
- Um exemplo de uso da propriedade `writing-mode` para texto vertical da direita para a esquerda:
  ```css
  p {
    writing-mode: vertical-rl;
  }
   ```

## 🏁 Conclusão
- A propriedade writing-mode é útil para personalizar a direção da escrita e o layout do texto em elementos HTML, permitindo que você adapte o texto para diferentes idiomas e estilos de escrita.
