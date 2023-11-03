# 🖼👯‍♂️ Propriedade Border Image Repeat em CSS

## ⁉ O que é a Propriedade `border-image-repeat`?
- A propriedade `border-image-repeat` em CSS permite controlar como as fatias da imagem de borda são repetidas ao redor de um elemento HTML.

## 💰 Valores da Propriedade `border-image-repeat`
- A propriedade `border-image-repeat` aceita valores que definem o comportamento de repetição das fatias, como:
  - `stretch`: Estica as fatias para preencher o espaço disponível.
  - `repeat`: Repete as fatias para cobrir o espaço.
  - `round`: Repete as fatias, ajustando-as para preencher o espaço sem deixar espaços em branco.

## 👩‍🏫 Exemplo de Uso
- Um exemplo de uso da propriedade `border-image-repeat` pode ser:

📌

  ```css
  .minha-classe {
    border-image-source: url('borda.png');
    border-image-slice: 20% fill;
    border-image-repeat: round;
  }
   ```
📌

## 🏁 Conclusão
- A propriedade border-image-repeat é útil para controlar como as fatias da imagem de borda são distribuídas ao redor de um elemento HTML, permitindo personalizar a aparência das bordas com diferentes padrões de repetição.
