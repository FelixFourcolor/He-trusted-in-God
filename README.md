# He trusted in God
"He trusted in God" in Handel's Messiah, arranged for Minecraft's noteblocks.

Recording: https://www.youtube.com/watch?v=jQLKgxHWafE

## Arrangement
Instrumentation:
* Soprano: bell
* Alto: bit
* Tenor: iron xylophone
* Bass: guitar
* Violin I (mostly double soprano): flute
* Violin II (mostly double alto): harp
* Viola (mostly double tenor): harp
* Bassoon (mostly double bass): didgeridoo
* Continuo: bass

Tranposed up 3 semitones to better fit noteblock's ranges. However, a few notes still do not fit, then they are either transposed up/down an octave or played by a different instrument, depending on which sounds better to me.

## Play requirements
Minecraft java 1.19+. 

Go to Music & Sounds setting, turn on Directional Audio and turn down Jukebox/Note Blocks sound level to 75% (otherwise it's too loud).

## Easy install 
Copy the [World](https://github.com/FelixFourcolor/He-trusted-in-God/tree/main/World) folder into your saves. 

To obtain the folder, you may clone the repo or use third-party tools such as [Down-Git](https://minhaskamal.github.io/DownGit) to download it.

## Build from source
### Build requirements
* python 3.10+
* pip

### Overview of the build process
The structure is auto-generated using [noteblock-generator](https://github.com/FelixFourcolor/noteblock-generator). The program takes [src.json](https://github.com/FelixFourcolor/He-trusted-in-God/blob/main/src.json) which defines the composition, and generates the structure inside an existing Minecraft world.

### Step-by-step guide

1. Install the latest version of [noteblock-generator](https://github.com/FelixFourcolor/noteblock-generator):
    ```
    pip install --upgrade noteblock-generator
    ```
    Configure your PATH so that `noteblock-generator` is executable on the command line.

2. Obtain [src.json](https://github.com/FelixFourcolor/He-trusted-in-God/blob/main/src.json). You may clone the repo or download just that file.

3. Obtain a world in Minecraft java 1.19+. You may use your existing world or create a new one.


4. If you are inside the world, exit it first. Then,
    ```
    noteblock-generator --clear [path to src.json] [path to minecraft world]
    ```
    (See [noteblock-generator](https://github.com/FelixFourcolor/noteblock-generator)'s documentation for explanation and more build options.)
