# He trusted in God
Handel's Messiah - "He trusted in God" arranged for Minecraft's noteblocks.

Recording: https://www.youtube.com/watch?v=jQLKgxHWafE

## Arrangement
Noteblock capabilities are quite limited, so lots of compromises had to be made.

Key: E-flat minor (transposed up 3 semitones from original)

Tempo: quarter note = 150 bpm (about 25% faster than a typical performance)

Instrumentation:
* Bassoon: transposed down 1 octave, played by didgeridoo
* Double bass: played by bass
* Viola: played by harp
* Violin II: played by harp
* Violin I: played by flute
* Bass: played by guitar
* Tenor: played by iron xylophone
* Alto: played by bit
* soprano: transposed up 1 octave, played by bell

## Play requirement
Minecraft java 1.18+

## Easy install 
Copy the `World` folder into your saves. 

To obtain the folder, you may clone the repo or use third-party tools such as [Down-Git](https://minhaskamal.github.io/DownGit) to download it.

Or,

## Build from source
### Build requirements
* python 3.10+
* pip
* git (optional)

### Overview of the build process
The structure is built automatically using a python program called `noteblock-generator` (available on PyPI). The program takes `src.json` (included in this repo) which defines the composition, and generates the structure inside an existing Minecraft world.

### Step-by-step guide

1. Install `noteblock-generator`:
    ```
    pip install noteblock-generator
    ```
    Configure your PATH so that `noteblock-generator` is executable on the command line.

2. Obtain `src.json`. You may clone the repo or download just that file.

3. Obtain a Minecraft java 1.18+ world. You may use an existing world or create a new one. 

    For maximum performance, create a new world in creative mode, peaceful difficulty, superflat type, and no generated structures.

    If you are inside the world, exit it before proceeding to the next step.

4. Generate:
    ```
    noteblock-generator [path to src.json] [path to minecraft world] --clear
    ```


Checkout [noteblock-generator](https://github.com/FelixFourcolor/noteblock-generator)'s documentation which explains how the program works and more build options.

## License
Do whatever you want.
