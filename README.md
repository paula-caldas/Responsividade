
# Responsividade

Essa página da web  é uma introdução à responsividade, apresentando um design moderno com foco na experiência do usuário tanto em dispositivos móveis quanto em desktops.


## Funcionalidades


### 1. **Estruturação Básica e Semântica**:
   - Utilização de tags semânticas como `<main>` e `<footer>`, melhorando a acessibilidade e a organização do conteúdo.

### 2. **Responsividade**:
   - **Media Query** para adaptar o layout a diferentes larguras de tela (ex: a partir de 700px, o layout muda de vertical para um design em duas colunas).
   - O `body` e o `main` ajustam o seu padding e layout conforme o tamanho da tela, garantindo uma boa apresentação tanto em dispositivos móveis quanto em telas maiores.
   
### 3. **Interatividade no Link**:
   - O link "Saiba mais" muda de cor e estilo (negrito) quando o usuário passa o mouse por cima (efeito `hover`).

### 4. **Lista Visualmente Organizada**:
   - A lista de benefícios é organizada de forma clara e legível:
     - Itens numerados estilizados com grandes números visuais e descrições ao lado.
     - Organização vertical com espaçamento entre os itens, garantindo legibilidade.

### 5. **Layout Centralizado**:
   - O conteúdo do `main` está centralizado na tela, melhorando a apresentação em telas menores e maiores.

### 6. **Uso de Flexbox**:
   - Na versão para telas maiores (a partir de 700px), o layout passa a utilizar o `display: flex` no `main`, organizando os elementos em duas colunas e ajustando os itens de forma flexível.

### 7. **Suporte à Experiência Móvel**:
   - Utilização da meta tag `viewport` para garantir que o layout seja responsivo em dispositivos móveis, ajustando o zoom e a escala adequadamente.


## Aprendizados

O que você aprendeu construindo esse projeto? 

1. **Mobile First**: Focar primeiro na estrutura para dispositivos móveis, onde os itens ficam em layout vertical, e depois ajustar para o desktop.
2. **Unidades de medida relativa**: Uso de `rem` em vez de `px`, facilitando a adaptação da página em diferentes dispositivos.
3. **Uso de `:root`**: Definir `font-size: 62.5%` para facilitar a conversão de `px` em `rem` (1rem = 10px).
4. **Pseudoclasse `:first-child`**: Para estilizar o primeiro elemento entre irmãos.
5. **Seleção de elementos consecutivos**: Uso de `h1 + p` para estilizar um `p` que segue diretamente um `h1`.
6. **Media Queries**: Adaptar o layout para diferentes tamanhos de tela com `@media (min-width: X)`.
7. **Seleção de elementos diretos**: Uso de `main > div` para aplicar estilos diretamente ao primeiro nível de `div`.

## Screenshots

![App Screenshot](https://i.imgur.com/fkES85P.png)

