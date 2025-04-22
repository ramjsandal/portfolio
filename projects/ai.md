# Artificial Intelligence / Procedural Content Generation

### Procedurally Generated 2D Caves| [github](https://github.com/ramjsandal/PCG) | [itch](https://shebloong.itch.io/random-caves)

![alt text](nurseryCrime.png)

Languages/Tools used: C#, Unity, Git

Created a 2D cave generator based on [this paper by Johnson et al.](https://dl.acm.org/doi/10.1145/1814256.1814266) and [this book by Derek Yu](https://www.amazon.com/Spelunky-Boss-Fight-Books-Derek/dp/1940535115). Planned out a random high level path and room layouts using a custom algorithm and then used cellular automata to generate each individual room based on their default layout and their neighboring rooms and then did a smoothing pass over the whole map. 