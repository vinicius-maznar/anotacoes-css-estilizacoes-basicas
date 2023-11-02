# 🖼 Background Attachment em CSS

## ⁉ O que é `background-attachment`?
- `background-attachment` é uma propriedade CSS que determina se a imagem de fundo de um elemento se move com o conteúdo da página ou se permanece fixa em relação à janela de visualização do navegador.

## 💰 Valores Principais
- `background-attachment` aceita dois valores principais:
  - `scroll`: A imagem de fundo rola juntamente com o conteúdo da página à medida que o usuário faz scroll.
  - `fixed`: A imagem de fundo permanece fixa em relação à janela de visualização, criando um efeito de paralaxe.

## 🌌 Paralaxe com `fixed`
- Quando `background-attachment` é definido como `fixed`, a imagem de fundo permanece no mesmo lugar, criando um efeito de paralaxe à medida que o usuário rola a página.

## ⚠ Precauções com `fixed`
- Usar `background-attachment: fixed;` em imagens de fundo de elementos grandes pode levar a problemas de desempenho, especialmente em dispositivos móveis.

## 👩‍🏫 Exemplo de Uso

📌

- Um exemplo de uso para criar um efeito de paralaxe pode ser:
  ```css
  .minha-classe {
    background-image: url('imagem.jpg');
    background-attachment: fixed;
  }
   ```
📌

## 🏁 Conclusão
- A propriedade background-attachment permite controlar se uma imagem de fundo se move com o conteúdo da página ou permanece fixa em relação à janela de visualização.
- É útil para criar efeitos visuais interessantes, como o efeito de paralaxe, mas requer consideração quanto ao desempenho em dispositivos móveis.
