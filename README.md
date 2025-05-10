#In main branh game2.py with neessary textures jpgs contains the functionalities of the game "Globe Runner" -------

#working methdolgy based on a graph code given below.
graph TD
  A[Start Screen] -->|Press F1| B(Game Active)
  B --> C{Collision?}
  C -->|Match Color| D[Score +1]
  C -->|Black Ball| E[Score -1]
  C -->|Wrong Color| F[Game Over]
  D -->|Score %15 == 0| G[Level Up]
  G --> H[Increase Speed]


