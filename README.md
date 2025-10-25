import pygame

pygame.mixer.init()
pygame.mixer.music.load("gentle-prelude-30-seconds-piano-352020.mp3")
pygame.mixer.music.play()
while pygame.mixer.music.get_busy():
    continue
