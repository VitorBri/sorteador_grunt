# Sorteador

Um projeto simples para sortear números aleatórios com base em um valor máximo fornecido pelo usuário. Desenvolvido com HTML, CSS (Less) e JavaScript, e automatizado com Grunt para tarefas de build.

## Começando

Siga as instruções abaixo para configurar e rodar o projeto localmente.

### Pré-requisitos

Antes de começar, você precisará ter instalado:

- [Node.js](https://nodejs.org/) (v18 ou superior)
- [Grunt](https://gruntjs.com/) (instalado globalmente via npm)

### Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/VitorBri/sorteador.git
   cd sorteador
   ```

2. Instale as dependências:

   ```bash
   npm install
   ```

3. Rode o projeto em modo de desenvolvimento:

   ```bash
   grunt
   ```

   Isso iniciará o `watch`, que monitora mudanças nos arquivos Less e HTML.

4. Para gerar a versão de produção (minificada e otimizada):

   ```bash
   grunt build
   ```

   Isso criará uma pasta `dist` com os arquivos prontos para deploy.

### Como usar

1. Abra o arquivo `dev/index.html` no navegador (ou `dist/index.html` após o build).
2. Insira um número máximo no campo de entrada.
3. Clique em "Sortear Número" para gerar um número aleatório entre 1 e o valor inserido.

## Licença

Este projeto está sob a licença [MIT](https://opensource.org/licenses/MIT).
