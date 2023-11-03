# ⛲🆎 Propriedade `text-overflow` em CSS

## ⁉ O que é a Propriedade `text-overflow`?
- A propriedade `text-overflow` em CSS é usada para controlar como o conteúdo de um elemento deve ser tratado quando ele transborda (extrapola) seu contêiner.

## 💰 Valores da Propriedade `text-overflow`
- A propriedade `text-overflow` aceita os seguintes valores:
  - `clip`: Valor padrão, que faz com que o texto extrapola seja cortado e não exibido.
  - `ellipsis`: Adiciona reticências "..." ao final do texto que transborda o contêiner.
  - `string`: Permite definir um texto personalizado para indicar o texto truncado.

## ⛲🆎 Uso Comum da Propriedade `text-overflow`
- A propriedade `text-overflow` é frequentemente usada em combinação com as propriedades `overflow` e `white-space` para criar um comportamento de texto truncado adequado.

## 👩‍🏫 Exemplo de Uso
- Um exemplo de uso da propriedade `text-overflow` com valor `ellipsis`:

📌
  ```css
  .overflow-container {
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
  }
   ```
📌

## 🏁 Conclusão
- A propriedade text-overflow é útil para controlar como o texto que excede seu contêiner deve ser tratado, permitindo que você indique truncamento com reticências ou um texto personalizado.
