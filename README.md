# CloneMC-V2.0-Entirely-In-C-and-Open-Gl-1.1
CloneMC is a recreation of Beta 1.7.3 designed to run especially on older systems and hardware with just C programming and Open Gl 1.1 Rendering. All of the documentation and what files and mutations cause within each other is in the docx files. This program had much better boilerplates and C code to actually be able to achieve massive frame rates and actually look like the real deal compared to the first version. However, this was mainly a side project, and beta 1.7.3 probably was old enough to run fine on older systems and this repo may not be updated frequently. Texture and UV mapping and core boilerplates was significantly improved compared to first verion. Even with the many metadata files, many of the core components and features have been added to look and run like the real deal with singleplayer/multiplayer

The github repo is a bit of a mess, but could be fixed soon

## Recommended to Extract Zip Folder With 7-zip and RENAME EXECUTABLE TO SOMETHING SHORTER as it may fail on some systems

To run the program, click on code and download the source code zip file, extract the contents and the exe should be there to click on as well as having assets folder, 

### It is recommended to test out worlds like Beta 1.7.3 Survival World to see the full demonstration of this program


<img width="959" height="484" alt="Screenshot 2026-07-15 175633" src="https://github.com/user-attachments/assets/d742c675-1356-46f3-a832-6e696a3c0f0e" />

## Important, if any features want to be added like sprinting, unbreakable boats, or better UV mapping of textures like for the minecart, there is a license uploaded in the zip folder, which should go along decompiled java files of the version that can be used in a a basic chatgpt subsrcitption to give references and code to add features, however at this stage, handwritten code/undertanding of the program and coversion tools can help save a lot more time and implement featueres way better/faster. 


The project currently is designed to reproduce and basically has almost every implementations of gameplay, world behavior, visual style, menus, entities, redstone systems, and even able to load, render, and save Java worlds properly. Has Both Proper Singleplayer And Multiplayer Support In the Program

CloneMC V2.0 this time also had extensive development and technical documentation for all aspects of the program

Complete engine architecture
Source-directory responsibilities
C, header, and include-manifest roles
State-mutation ownership
Rendering order
Chunk lifecycle
World saving
NBT and McRegion storage
Entities and models
Redstone
GUI systems
Performance budgets
Testing and debugging
How to add new blocks, items, entities, recipes, and screens

<img width="958" height="500" alt="Screenshot 2026-07-14 182134" src="https://github.com/user-attachments/assets/cb79f0d6-0bb0-4fa1-877c-ee035cb43ad6" />

To Run the program: download the source code zip from the main page, and click on the exe file, there is a good test world 

Unlike modern voxel engines, CloneMC uses entirely C and uses Open Gl 1.1 rendering which was able to get hundreds of FPS and have good performance in systems!

<img width="958" height="482" alt="Screenshot 2026-07-15 183611" src="https://github.com/user-attachments/assets/ca96722a-3162-44e3-9cac-632ed30321ec" />


Example of Implementation: World Generation includes Java-derived behavior for:

Seeded deterministic generation
Perlin and octave noise
Terrain density interpolation
Biome temperature and humidity
Grass, dirt, sand, gravel, stone, and bedrock layers
Oceans, beaches, caves, ores, vegetation, and snow
Surface replacement based on biome
Population and decoration ordering
Overworld and Nether-style dimensions
Chunk loading, generation, population, lighting, and meshing as separate states
Terrain generation is isolated from rendering. Visibility checks and terrain drawing are not permitted to generate hidden chunks.
