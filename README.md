# CSCI-166-Pacman

[Pacman Docs](https://ale.farama.org/environments/ms_pacman)

## Reflection
I chose the environment of Pacman because the game of Pacman was a childhood game I always played growing up. This game gives the feeling of nostalgia which is why I felt drawn to choose this environment. I also chose this environment because of the environement and training involving the agent navigating a maze to collect pellets but also reactive in avoiding ghosts so that it does not lives. Once all lives are lost, no rewards are able to be gained to improve the score.
  
  Earlier at the beginning of the training, it was difficult for Pacman to navigate and move around the maze and at first, it made just one move and stopped. It improved as the training developed and was able to move around and get navigate and get more points around the maze. The main challenges of this was navigating around the maze to get more points. Once that issue was resolved, the next challenge that appeared was Pacman avoiding the ghost to prevent losing lives. To improve the code, I edited the Epsilon schedule to have slower decay and more exploration. I also edited the reward clipping value changing it from False to True. 
