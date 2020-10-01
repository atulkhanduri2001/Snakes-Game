Name of program:- SNAKES GAME

Description- This is a old school snakes game . 

Requirements to run program:

1. Any OS like windows,linux,etc 
2. Python 3.7.0 
3. IDE-PyCharm Edition 2020.2.1

Installation required :

Following libraries to be installed: 
1. import pygame
2. import random
3. import os
4. import time

Steps need to be followed for working of programs:

1. All the music and photos should be saved in the same directory in which program is.
2. In,  
           """bgimg = pygame.image.load("sn2.jpg")
            bgimg2=pygame.image.load("sn1.jpg")
            bgimg2 = pygame.transform.scale(bgimg2, (screen_width, screen_height)).convert_alpha()
            bgimg = pygame.transform.scale(bgimg, (screen_width, screen_height)).convert_alpha()
            gameWindow.blit(bgimg2, (0, 0))""""
            
                               enter the background image name which you want to put in this game in place of sn1 and sn2.
3. In,
       """pygame.mixer.music.load('water.mp3')
           pygame.mixer.music.play()"""
           
           enter the music file name or sound effect file name followed by '.mp3' 

4. You can also change color in colors            
             
