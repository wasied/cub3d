# cub3d
A Wolfenstein 3D-like game made with raycasting in C

I made this game for School42 with my mate (cjulienn).

### My work:
- Raycasting algorithm
- Fake 3D walls effect
- Translating the algorithm into the rendering part
- Wall texturing (depending on the wall orientation)
- Collisions with walls
- Player movements
- Troubleshooting

### My mate's work:
- Base structure
- Parsing and error cases
- MiniLibX drawing base
- Key-press detection system
- Allocation and deallocation
- Minimap bonus
- Crosshair bonus


# How to run it?
It works on **MacOS** and ***Linux** (only if you install by yourself mlx_linux in the repo ~ makefile is automatically detecting it)*.  
You can just ``git clone https://github.com/MaaxIT/cub3d`` and run ``make`` to compile the project.  
When it's fully compiled, use ``./Cub3D your/map_path.cub`` to open a map (must have a .cub extension).  
