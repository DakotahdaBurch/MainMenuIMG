# MainMenuIMG
This is how i set it up
from time import sleep
import pygame
pygame.init()
from random import uniform, randint


windowSize = [1366, 768]
screen = pygame.display.set_mode(windowSize)
backcolour = pygame.color.Color('#010520')

#sets the window size
gameDisplay = pygame.display.set_mode((1366, 768))

#loads in your pics to use later
Titlep = pygame.image.load('Title.jpeg')
WBox = pygame.image.load('Box.jpeg')
WSBox = pygame.image.load('RatingBox.jpeg')
WSBox1 = pygame.image.load('RatingBox.jpeg')
WSBox2 = pygame.image.load('RatingBox.jpeg')
WSBox3 = pygame.image.load('RatingBox.jpeg')
CrocketdileGame = pygame.image.load('Crocketdile4.jpg')
Gthumb = pygame.image.load('GreenThumb.jpeg')
Gthumb1 = pygame.image.load('GreenThumb.jpeg')
Gthumb2 = pygame.image.load('GreenThumb.jpeg')
Gthumb3 = pygame.image.load('GreenThumb.jpeg')
Rthumb = pygame.image.load('RedThumb.jpeg')
Rthumb1 = pygame.image.load('RedThumb.jpeg')
Rthumb2 = pygame.image.load('RedThumb.jpeg')
Rthumb3 = pygame.image.load('RedThumb.jpeg')
Arrow = pygame.image.load('Arrow.png')
Gamemenu = pygame.image.load('Whitesq2.jpg')



#DISPLAY BACKGROUND
pygame.display.update()
# sleep(1)


finished = False
while not finished:
    #mouse location
    mouseX = pygame.mouse.get_pos()[0]
    mouseY = pygame.mouse.get_pos()[1]
    screen.fill(backcolour)
    gameDisplay.blit(Titlep, (200, 40))
    gameDisplay.blit(WBox, (300, 300))
    gameDisplay.blit(WSBox, (100, 680))
    gameDisplay.blit(WSBox1, (400, 680))
    gameDisplay.blit(WSBox2, (700, 680))
    gameDisplay.blit(WSBox3, (1000, 680))
    gameDisplay.blit(CrocketdileGame, (73, 470))
    gameDisplay.blit(Gthumb, (110, 697))
    gameDisplay.blit(Gthumb1, (410, 697))
    gameDisplay.blit(Gthumb2, (710, 697))
    gameDisplay.blit(Gthumb3, (1010, 697))
    gameDisplay.blit(Rthumb, (150, 696))
    gameDisplay.blit(Rthumb1, (450, 696))
    gameDisplay.blit(Rthumb2, (750, 696))
    gameDisplay.blit(Rthumb3, (1050, 696))
    gameDisplay.blit(Arrow, (1250, 530))







#DISPLAY YOU ARE HERE

#GAME WILL NOW EXIT UNLESS YOU LOOP IT OR ADD AN input

   
pygame.quit()
quit()
