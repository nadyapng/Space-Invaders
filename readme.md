# Space Invaders README

This file contains instructions on running the game and configurations that can be made.


## How to run the code

The game can be started by executing 'gradle run' in the terminal and can be exited by simply closing the game window.

## Design patterns used

- Factory Method
    - Classes involved:
        - ProjectileFactory, SlowProjectileFactory, FastProjectileFactory, PlayerProjectileFactory, EnemyProjectile, PlayerProjectile, SlowProjectile, FastProjectile
- Builder Pattern (Bunker)
    - Classes involved:
        - Bunker, BunkerBuilder, BunkerDirector, NormalBunkerBuilder
- Builder Pattern (Enemy)
    - Enemy, EnemyBuilder, EnemyDirector, NormalEnemyBuilder
- State Pattern
    - Classes involved:
        - DestructionState, DestructionState1, DestructionState2, DestructionState3, Bunker
- Strategy Pattern
    - Classes involved:
        - ShootStrategy, SlowShootStrategy, FastShootStrategy, Enemy


## Configuration information

The game configurations can be edited in the config.json file, in the same format as was given to us. The game supports 4 colour configurations for the spaceship: blue, green, pink and red. Simply change the colour value for the player in the JSON file to any of these colours to configure it. If an invalid colour is given, the spaceship will default to blue.

## Javadocs
Javadocs for the game can be found in src/javadocs.