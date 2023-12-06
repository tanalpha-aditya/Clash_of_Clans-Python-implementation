# Clash of Clans game
- **Bonus** :
    - Building levels are implemented by hardcoding ( as asked )
        - Cannon and Wizard Tower : implemented all features
        - wall : Implemented all features, Damage to King/queen and all troops in the viscinity 
                 of the wall

- Stealth Archer ( 10 ) named - starcher
    - 10 sec invisibility ( no buildings can attack ).
    - After 10 sec, it will behave like normal archer with different name S.ARCHER. 
    - Splash Damage implemented by walls even in steath mode

- Healer 
    - All attributes given are implemented
    - Will first go to the nearest injured troop.
    - No injured troop, then healer will not move.
    - Heals all troops on that coordinate ( air + ground + King/ queen )
    - If ONLY healer is alive then game ends.

- To run the game : `python3 game.py`
- To view replays : `python3 replay.py`  and select the replay you want to watch according to mentioned date and time.
- For Victory : All buildings apart from walls get destroyed from the map in all three levels.
- For Defeat : If all troops and King die before destroying all buildings apart from walls.

## Controls :

### Hero :

- w : move up
- a : move left
- d : move right
- s : move down
- 1 : Special Attack
- space : Normal Attack

### Barbarian :

- z : spawn at point 1
- x : spawn at point 2
- c : spawn at point 3

### Dragon :

- v : spawn at point 1
- b : spawn at point 2
- n : spawn at point 3

### Archer :

- i : spawn at point 1
- o : spawn at point 2
- p : spawn at point 3

### Balloon :

- j : spawn at point 1
- k : spawn at point 2
- l : spawn at point 3

### St. Archer :

- 6 : spawn at point 1
- 7 : spawn at point 2
- 8 : spawn at point 3

### Healer :

- 3 : spawn at point 1
- 4 : spawn at point 2
- 5 : spawn at point 3

q : Quit Game

## Assumptions :

- Rage and Heal Spell can be applied multiple times.
- The limit for troops in each level is as follows :
    - Barbarians : 10
    - Archers : 7
    - Balloon : 5
    - Dragon : 3
    - Healer : 5
    - St. Archer : 7 
- You have to choose the type of troop movement at start of the game.
- You have to choose the hero after each level.