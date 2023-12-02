- 👋 Himport pygame
import sys

# Inicialização do Pygame
pygame.init()

# Configurações da tela
largura, altura = 800, 600
tela = pygame.display.set_mode((largura, altura))
pygame.display.set_caption("Meu Jogo do Super Mario")

# Cores
branco = (255, 255, 255)

# Personagem
personagem = pygame.Surface((50, 50))
personagem.fill((255, 0, 0))
personagem_rect = personagem.get_rect()
personagem_rect.center = (largura // 2, altura // 2)

# Loop principal
while True:
    for evento in pygame.event.get():
        if evento.type == pygame.QUIT:
            pygame.quit()
            sys.exit()

    # Lógica do jogo

    # Renderização
    tela.fill(branco)
    tela.blit(personagem, personagem_rect.topleft)

    pygame.display.flip()

    # Controle de atualização de frames por segundo (FPS)
    pygame.time.Clock().tick(60)
i, I’m @leonardo6677
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
leonardo6677/leonardo6677 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
