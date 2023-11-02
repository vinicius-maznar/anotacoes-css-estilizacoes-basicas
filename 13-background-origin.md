# 🖼 Background Origin em CSS

## ⁉ O que é `background-origin`?
- `background-origin` é uma propriedade CSS que define o ponto de origem a partir do qual uma imagem de fundo ou cor de fundo é renderizada em um elemento.

## 🧩 Valores Principais
- `background-origin` aceita três valores principais:
  - `padding-box`: A imagem de fundo começa a ser renderizada a partir da borda interna do padding box do elemento.
  - `border-box`: A imagem de fundo começa a ser renderizada a partir da borda externa do border box do elemento.
  - `content-box`: A imagem de fundo começa a ser renderizada a partir da borda interna do content box do elemento.

## 💰 Valor `padding-box`
- Com `background-origin: padding-box;`, a imagem de fundo é renderizada a partir da borda interna da área de preenchimento do elemento.

## 💰 Valor `border-box`
- Com `background-origin: border-box;`, a imagem de fundo é renderizada a partir da borda externa do elemento, incluindo a borda.

## 💰 Valor `content-box`
- Com `background-origin: content-box;`, a imagem de fundo é renderizada a partir da borda interna do conteúdo do elemento, excluindo o preenchimento e a borda.

## 👩‍🏫 Exemplo de Uso
- Um exemplo de uso para definir o ponto de origem de uma imagem de fundo pode ser:

📌

  ```css
  .minha-classe {
    background-image: url('imagem.jpg');
    background-origin: padding-box;
  }
   ```

📌

## 🎆 Conclusão
- A propriedade background-origin permite controlar o ponto de origem a partir do qual uma imagem de fundo ou cor de fundo é renderizada em um elemento.
- Isso é útil para ajustar o layout e a aparência de elementos, especialmente quando se trabalha com bordas e preenchimento.
