# Matador-de-monstros- Vue.js

Este é um jogo simples de combate onde o jogador enfrenta um monstro. Desenvolvido utilizando **Vue.js**, **HTML**, **CSS** e **JavaScript**, o jogo oferece uma experiência dinâmica, com ações de ataque, cura e ataques especiais. O jogador pode interagir com o monstro e decidir suas ações, enquanto monitora sua própria barra de vida e a do monstro.

Este projeto foi desenvolvido como parte de um exercício de um **curso de Vue.js**, com o objetivo de praticar conceitos básicos e intermediários dessa tecnologia.

## Funcionalidades

- **Barra de Vida**: O jogo exibe barras de vida para o jogador e para o monstro, mostrando o quanto de vida resta para ambos.
- **Ações Disponíveis**:
  - **Ataque**: O jogador realiza um ataque, mas o monstro também contra-ataca. Os valores dos ataques são gerados aleatoriamente, e a força do ataque do monstro é maior.
  - **Cura**: O jogador pode recuperar uma quantidade de vida, gerenciada aleatoriamente.
  - **Ataque Especial**: O jogador tem uma chance de realizar um ataque mais forte que o normal.
  - **Desistir**: O jogador pode escolher desistir da batalha a qualquer momento.
- **Vencedor**: Se o jogador ou o monstro perderem toda a vida, uma mensagem aparece indicando quem ganhou ou perdeu.

## Como jogar

1. **Inicie o jogo**: Ao carregar a aplicação, clique no botão para iniciar um novo jogo.
2. **Escolha sua ação**: Após o início, o jogador pode escolher entre 4 opções:
   - **Ataque**: Lança um ataque contra o monstro, mas também sofre o contra-ataque.
   - **Cura**: Recupera uma parte da sua vida.
   - **Ataque Especial**: Um ataque mais forte, com chance de causar mais dano.
   - **Desistir**: Se o jogador não quiser mais continuar a batalha, pode desistir.
3. **Acompanhe a batalha**: A cada ação do jogador, o monstro também executa sua ação automaticamente.
4. **Fim de Jogo**: O jogo termina quando a vida do jogador ou do monstro chega a 0, e uma mensagem de vitória ou derrota é exibida.

## Como rodar o projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/ThaisOlivera0/matadorDeMonstros.git
   
2. Navegue até a pasta do projeto:
    ```bash
    cd matadorDeMonstros
   
4. Instale as dependências:
     ```bash
    npm install
    
5. Rode o servidor de desenvolvimento:
    ```bash
   npm run serve
   
6. Abra o navegador e acesse:
   http://localhost:8080

## Tecnologias utilizadas

- **Vue.js**: Framework JavaScript para construção da interface.
- **CSS/HTML**: Para estilização e estruturação da interface.
- **JavaScript**: Para lógica do jogo e interações.

## Contribuições

Sinta-se à vontade para fazer contribuições, como melhorias no design, na lógica do jogo, ou até mesmo na adição de novos recursos! Se você encontrar algum erro, por favor, abra uma *issue* no repositório.
