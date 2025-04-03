# Introdução
- Qual a ideia principal do seu jogo? 
- Que tipo de experiência você quer dar para o seu jogador?

### Gênero
O jogo desenvolvido pertence ao gênero **Roguelike** um subgênero dos jogos de aventura e ação caracterizado por mapas gerados proceduralmente (ou semi-aleatoriamente), progressão baseada em melhoria de personagem e morte permanente. Neste jogo de plataforma 2D com progressão vertical, o jogador controlará um guerreiro que deve escalar a lendária Torre de Babel, enfrentando desafios, derrotando inimigos e coletando fragmentos de idiomas para restaurar a comunicação da humanidade.

### História

Segundo a lenda, a humanidade construiu uma torre tão grande que alcançou os céus. Enfurecidos, os deuses lançaram uma maldição, fragmentando a linguagem humana em vários idiomas e dividindo os povos em grupos incapazes de se comunicar entre si. No meio desse caos, um guerreiro determinado decide desafiar os deuses e escalar a Torre de Babel para coletar os **Fragmentos de Idiomas** e restaurar a linguagem unificada.

A cada 10 andares, o guerreiro enfrentará um deus guardião da torre. Ao derrotá-lo, ele recuperará um dos fragmentos de idioma e desbloqueará uma nova classe de guerreiro, representando o povo que falava aquele idioma, como Arqueiro (Inglês), Mago (Espanhol), entre outros. Entretanto, a ascensão não será fácil: quanto mais alto ele sobe, mais rarefeito o ar se torna, tornando a jornada progressivamente mais difícil.

Como em um autêntico Roguelike, o guerreiro é destinado a falhar em suas primeiras tentativas. Quando ele sucumbe à torre, um novo guerreiro assume seu lugar e herda toda a \textbf{Vontade Ancestral}, uma moeda adquirida ao derrotar inimigos. Essa moeda pode ser utilizada no pé da torre para desbloquear melhorias permanentes, tornando cada nova tentativa mais promissora. O objetivo final é chegar ao topo, derrotar o último chefe e reunir todos os Fragmentos de Idioma, restaurando

### Estrutura do Jogo
O desenvolvimento do jogo seguirá a estrutura básica de um jogo de plataforma 2D com progressão vertical, contemplando:
#### Loop Principal
O jogo rodará em um ciclo contínuo, onde a lógica será constantemente verificada. Durante o loop, serão processadas as seguintes ações:
- Atualização da posição do jogador e dos inimigos.
- Detecção de colisões com plataformas, armadilhas e inimigos.
- Aplicação de dano e cálculo de morte para personagens.
- Verificação de eventos especiais, como salas de buffs ou chefes.
- Gerenciamento da sucessão de guerreiros em caso de morte.

