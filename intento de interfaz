import pygame,sys
from pygame.locals import *
from random import randint

pygame.init()
ventana = pygame.display.set_mode((700,600))
pygame.display.set_caption("El gato extremo")

Mi_imagen= pygame.image.load("images.jpeg")
Fondo= pygame.image.load("image.png")

posX= 200
posY= 100


velocidad= 4
Blanco=(255,255,255)
Derecha = True

while True:
	ventana.fill(Blanco)
	ventana.blit(Mi_imagen,(posX,posY))
	ventana.blit(Fondo,(0,0))

	for event in pygame.event.get():
		if event.type == QUIT:
			pygame.quit()
			sys.exit()
		elif event.type == pygame.KEYDOWN:
			if event.key == K_LEFT:
				posX -= velocidad
			elif event.key == K_RIGHT:
				posX += velocidad
			elif event.key == K_UP:
				posY -= velocidad
			elif event.key == K_DOWN:
				posY += velocidad



	pygame.display.update()

