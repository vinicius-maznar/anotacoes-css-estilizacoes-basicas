# ⛲ Propriedade Overflow em CSS

## ⁉ O que é a Propriedade Overflow?
- A propriedade `overflow` é usada para controlar o comportamento de conteúdo que transborda (ultrapassa) o contêiner de um elemento HTML. Ela determina como o conteúdo que não cabe no contêiner deve ser tratado.

## 💰 Valores da Propriedade `overflow`
- Existem várias opções para a propriedade `overflow`. Os valores mais comuns incluem:
  - `visible`: O conteúdo ultrapassante é visível fora do contêiner.
  - `hidden`: Qualquer conteúdo que ultrapasse o contêiner é cortado e não é visível.
  - `scroll`: É exibida uma barra de rolagem, permitindo que o usuário role para ver o conteúdo ultrapassante.
  - `auto`: Semelhante a `scroll`, mas uma barra de rolagem é exibida apenas quando necessário.

## 👩‍🏫 Exemplo de Uso da Propriedade `overflow`
- Exemplo de uso da propriedade `overflow` para criar uma caixa com uma barra de rolagem vertical quando o conteúdo ultrapassar:

📌
  ```css
  .meu-contêiner {
    width: 300px;
    height: 200px;
    overflow: auto;
  }
   ```
📌

## 💡 Dica
- A propriedade overflow é útil para controlar o comportamento de conteúdo em caixas, divs e outros elementos, especialmente quando o espaço é limitado.
