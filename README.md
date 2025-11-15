# Ping Pong em Java

Um jogo clássico de ping pong feito em Java usando Swing para a interface gráfica.

## Como jogar

- Use as setas do teclado (↑ ↓) para mover sua raquete
- O mouse também controla a raquete
- Não deixe a bola passar pela sua raquete!
- Seus pontos ficam salvos no ranking

## Requisitos

- Java 8 ou superior
- Nada mais, só isso mesmo

## Como rodar

1. Compile os arquivos:
```bash
javac src/*.java
```

2. Execute o jogo:
```bash
java -cp src Jogo
```

Ou se preferir, abra no seu IDE favorito (Eclipse, IntelliJ, etc.) e rode a classe `Jogo`.

## Estrutura do projeto

- `Jogo.java` - Classe principal, controla o loop do jogo e eventos
- `Bola.java` - A bolinha que fica quicando
- `Menu.java` - Sistema de menus do jogo  
- `Ranking.java` - Tela de pontuação e ranking dos jogadores
- `Tela.java` - Gerencia a renderização na tela
- `CenarioPadrao.java` - Cenário principal do jogo
- Outros arquivos auxiliares para elementos gráficos e utilitários

## Funcionalidades

- Jogo de ping pong básico mas funcional
- Sistema de ranking que salva automaticamente
- Interface simples e responsiva
- Controles por teclado e mouse

