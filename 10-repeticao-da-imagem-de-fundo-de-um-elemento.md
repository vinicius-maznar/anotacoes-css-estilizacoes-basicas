# 👯‍♂️👯‍♂️ Repetição de Imagens de Fundo em CSS

## ⁉ O que é Repetição de Imagens de Fundo?
- A repetição de imagens de fundo refere-se à forma como as imagens usadas como fundo de elementos HTML são dispostas quando o tamanho do elemento é menor que o tamanho da imagem.

## 🧩 Propriedade `background-repeat`
- A propriedade `background-repeat` controla se e como uma imagem de fundo é repetida em relação ao elemento.
- Ela pode aceitar valores como `repeat`, `no-repeat`, `repeat-x` e `repeat-y`.

## 💰 Valor `repeat`
- `background-repeat: repeat;` permite que a imagem de fundo seja repetida tanto horizontal como verticalmente até preencher o elemento.

## 🚫 Valor `no-repeat`
- `background-repeat: no-repeat;` impede que a imagem de fundo seja repetida, exibindo-a apenas uma vez.

## ↔️ Valor `repeat-x` e ↕️ Valor `repeat-y`
- `background-repeat: repeat-x;` repete a imagem apenas horizontalmente.
- `background-repeat: repeat-y;` repete a imagem apenas verticalmente.

## 👩‍🏫 Exemplo de Uso
- Um exemplo de uso para controlar a repetição de uma imagem de fundo pode ser:

📌

  ```css
  .minha-classe {
    background-image: url('imagem.jpg');
    background-repeat: no-repeat;
  }
   ```
📌

## 🏁 Conclusão
- Controlar a repetição de imagens de fundo é importante para criar layouts esteticamente agradáveis e eficazes em design web.
- A propriedade background-repeat oferece controle sobre como as imagens de fundo são repetidas em relação aos elementos.
