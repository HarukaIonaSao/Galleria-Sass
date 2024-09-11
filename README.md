# 📸 Galleria

Bem-vindo ao **Galleria**, uma galeria de fotos estilosa construída com HTML, CSS e Sass! 🚀

## 🎯 Funcionalidades

- Navegação responsiva 🔄
- Cards de fotos interativos 📷
- Links para redes sociais 🔗
- Interface limpa e moderna 🎨

## 🛠️ Tecnologias Utilizadas

- **HTML5** 🖼️: Estrutura semântica do projeto.
- **CSS3** 🎨: Estilos responsivos e personalizações.
- **Sass (SCSS)** 💎: Pré-processador de CSS que melhora a organização e manutenção do código.
- **JavaScript** 💻: Scripts para acessibilidade e interações dinâmicas.
- **Font Awesome** 🎥: Ícones para redes sociais.

## 🚀 Pré-processamento com Sass

O projeto utiliza **Sass** para escrever estilos de forma mais eficiente e organizada. Aqui estão os principais benefícios de usar o Sass:

- 🌀 **Modularização**: Estilos divididos em diferentes arquivos para melhor organização.
- 🧬 **Variáveis**: Cores e tamanhos reutilizados ao longo do código, facilitando ajustes rápidos.
- 🎛️ **Mixins**: Blocos de código reutilizáveis, como centralização de flexbox e imagens de fundo.
- 🌐 **Responsividade**: Media queries dinâmicas para mobile first.

Exemplo de uso de **Sass** no projeto:
```scss
@use 'variables';
@use 'mixins';

.header {
  display: flex;
  justify-content: space-between;
  @include mixins.container;
  
  &-brand {
    color: variables.$primary-color;
    font-size: 3rem;
  }
}
```
https://user-images.githubusercontent.com/95101635/216840376-50f9e650-a130-4b30-9062-7dcd9ae58842.mp4


