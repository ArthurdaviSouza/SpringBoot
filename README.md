# SpringBoot
Modelo básico Java com Spring Boot com framework Gradle

Logica:
Foi criado um metodo para cada jogada, exemplo: Pedra, Papel ,...desta forma se houver mudanca no jogo, sera pontual e cada um segue a logica de validar apenas 1 jogador, visto que ja sabemos a jogada do jogador 1, precisamos saber se ele pode vencer ou não. Com base na lista na linha 10.
Primeiro valida se objetos de jogada são validos.
Qual tipo de objeto do jogador para validar o vencedor.
Com base no Desenho, temos as seguintes jogadas para definir o campeao:

Tesoura vence o papel
Tesoura vence o lagarto

Papel vence a pedra
Papel vence o Spock

Pedra vence o lagarto
Pedra vence a tesoura

lagarto vence Spock
Lagarto vence o papel

Spock vence a pedra
Spock vence a tesoura

Não foi finalizado  devido ao tempo, falta try catch e tratamentos de erros em geral.
