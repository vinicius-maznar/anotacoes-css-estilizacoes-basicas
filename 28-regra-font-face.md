# 🎭🆎 Regra @font-face em CSS

## 🖋⁉ O que é a Regra `@font-face`?
- A regra `@font-face` em CSS é usada para incorporar fontes personalizadas em um site, permitindo que você utilize fontes que não estão disponíveis nos sistemas dos usuários.

## 💠 Formato de Fontes
- A regra `@font-face` permite especificar fontes personalizadas em diferentes formatos, como TTF, WOFF, WOFF2, EOT, ou SVG, para garantir a compatibilidade com diversos navegadores.

## 📝 Definição de Fontes
- Ao usar a regra `@font-face`, você define uma fonte personalizada, dando-lhe um nome e especificando o local onde o arquivo da fonte está armazenado.

## 🛠 Uso da Fonte Personalizada
- Depois de definir a fonte com `@font-face`, você pode usá-la em seu CSS como se fosse uma fonte padrão, aplicando-a a elementos de texto.

## 💰 Exemplo de Uso
- Um exemplo de uso da regra `@font-face`:

📌

  ```css
  @font-face {
    font-family: 'MinhaFonte';
    src: url('minha-fonte.woff2') format('woff2');
  }

  body {
    font-family: 'MinhaFonte', sans-serif;
  }
   ```
📌

## 🏁 Conclusão
- A regra @font-face é essencial para incorporar fontes personalizadas em projetos web, expandindo as opções de design e garantindo que o texto seja exibido conforme desejado, independentemente das fontes disponíveis nos dispositivos dos usuários.
