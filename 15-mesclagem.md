# 🎭 Mesclagem em CSS

## ⁉ O que é Mesclagem?
- A mesclagem (ou blending) em CSS é uma técnica que permite combinar elementos visuais de camadas sobrepostas de uma forma criativa.

## 🧩 Propriedades de Mesclagem
- Existem duas propriedades principais de mesclagem:
  - `mix-blend-mode`: Define o modo de mesclagem para a camada atual em relação à camada abaixo.
  - `isolation`: Controla se um elemento é isolado das camadas subjacentes para mesclagem.

## 💰 Valores de `mix-blend-mode`
- `mix-blend-mode` aceita valores como `normal`, `multiply`, `screen`, `overlay`, `color-dodge`, `color-burn`, `exclusion`, entre outros.
- Cada valor afeta a maneira como a camada atual se mescla com a camada abaixo.

## 🧩 Propriedade `isolation`
- A propriedade `isolation` define se um elemento deve ser isolado das camadas subjacentes para mesclagem.
- Valores possíveis são `auto` (padrão) e `isolate`.

## 👩‍🏫 Exemplo de Uso
- Um exemplo de uso de mesclagem pode ser:

📌

  ```css
  .minha-classe {
    mix-blend-mode: multiply;
  }
   ```
📌

## 🎆 Conclusão
- A mesclagem em CSS é uma técnica poderosa para criar efeitos visuais criativos e sobreposições de elementos.
- As propriedades mix-blend-mode e isolation oferecem controle sobre como as camadas se combinam e se isolam.
