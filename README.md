# DungeonMinotauro.AppleAcademy
🐂 Dungeon Minotauro
Um jogo de aventura em modo texto feito em Swift, onde o jogador explora uma dungeon cheia de criaturas perigosas e enfrenta o poderoso Minotauro.
📜 Sobre o Projeto
Dungeon Minotauro é um RPG simples em terminal, inspirado em mecânicas de rolagem de dados como D20.
O objetivo é explorar salas, derrotar inimigos, coletar upgrades e, finalmente, vencer o chefão da dungeon.
Você pode:
Explorar direções (norte, sul, leste, oeste)
Enfrentar inimigos com rolagens de ataque (incluindo crítico e falha crítica)
Tentar fugir usando testes de dificuldade
Evoluir seu ataque ao derrotar inimigos
Chegar ao Minotauro e derrotá-lo!
🕹️ Como Jogar
Comandos básicos dentro do jogo:
Situação	Comandos
Encontro com inimigo	atacar ou fugir
Navegação	norte, sul, leste, oeste
Encerrar jogo	sair
O combate usa um sistema de rolagem de D20:
1 = falha crítica
20 = acerto crítico
Qualquer outro valor = ataque normal
Se você derrotar um inimigo (exceto o Minotauro), seu ataque aumenta em +1.
🧱 Estrutura da Dungeon
A dungeon é composta pelas seguintes salas:
Entrada da Dungeon
Corredor Sombrio
Sala das Armas
Túnel das Sombras
Anticâmara do Minotauro
Centro da Dungeon (Boss)
Cada sala pode ter:
Nome
Descrição
Direções de saída
Um inimigo (opcional)
⚔️ Inimigos
Os inimigos possíveis são:
🧌 Goblin
💀 Esqueleto
🕷️ Aranha
👻 Sombra
🐂 Minotauro (chefão)
Cada inimigo possui:
Vida
Ataque
Bônus de fuga (usado quando você tenta correr)
🚀 Como Executar
Abra o projeto no Xcode ou crie um arquivo main.swift.
Copie o código-fonte do jogo para o arquivo.
Execute com run no Xcode
ou via terminal:
swift main.swift
📁 Estrutura do Código
Direcao – Enum com direções possíveis
TipoInimigo – Tipos de inimigos
Inimigo – Classe que define cada inimigo
Sala – Classe que representa cada sala da dungeon
Jogador – Status do jogador
Funções principais:
combate()
mover()
tentarFugir()
mostrarSala()
criarDungeon()
🎯 Objetivo Final
Derrotar o Minotauro no centro da dungeon.
Ao vencer o chefão, o jogo exibe uma mensagem especial e encerra.
