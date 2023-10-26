# How pygame works

1. Set up pygame 
```
pip install pygame
```

2. Initialize pygame
```{python}
import pygame
pygame.init()
```

3. Create a game window
- Define width and height of screen , set title

```
screen = pygame.display.set_mode((width,height))
pygame.display.set_caption("Basic Pygame Game")
```

4. Create a Game Loop

```
running = True
while running :
	for event in pygame.event.get():
		if event.type == pygame.QUIT :
			running = False
	screen.fill((0,0,0))

	pygame.display.update()

```

5. Update Game Logic and user input

6. Draw Game Graphics

7. Display Score and Game Over

8. Add Sound and Music

9. Handle Game over and cleanup
```
pygame.quit
```
