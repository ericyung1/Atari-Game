# Atari-Game

Developer Notes:
* In order to have a two digit score board so that my game can go beyond 9 points, I used digit graphics that are 3 bits across
* These two digits can fit within the PF1 register and we can use a mask to get just the ones or tens place with the and operator