# He trusted in God
"He trusted in God" in Handel's Messiah, arranged for Minecraft's noteblocks.

Recording: https://youtu.be/jQLKgxHWafE

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
Minecraft Java 1.20+ to play the pre-built world; 1.19+ if you build from source.

Go to Music & Sounds settings and turn on Directional Audio. Optionally, turn down Master Volume to about 70% to 80%, otherwise it might be a bit too loud (but of course this depends on your speakers).


## Easy install 
Copy the [World](https://github.com/FelixFourcolor/He-trusted-in-God/tree/main/World) folder into your saves. 

To obtain the folder, you may clone the repo or use third-party tools such as [Down-Git](https://minhaskamal.github.io/DownGit) to download it.

## Build from source
### Build requirements
* python 3.10-3.12
* pip

### Overview of the build process
The structure is auto-generated using [noteblock-generator](https://pypi.org/project/noteblock-generator/0.2.1). The program takes [src.json](https://github.com/FelixFourcolor/He-trusted-in-God/blob/main/src.json) which defines the composition, and generates the structure inside an existing Minecraft world.

### Step-by-step guide

1. Install noteblock-generator 0.2.1 (must be this exact version):
    ```sh
    pip install "noteblock-generator==0.2.1"
    ```
    Configure your PATH so that `noteblock-generator` is executable on the command line.

2. Obtain [src.json](https://github.com/FelixFourcolor/He-trusted-in-God/blob/main/src.json). You may clone the repo or download just that file.

3. Obtain a world in Minecraft Java 1.19+. You may use your existing world or create a new one.

4. Run:
    ```sh
    noteblock-generator [path to src.json] [path to minecraft world]
    ```
    See [noteblock-generator](https://pypi.org/project/noteblock-generator/0.2.1) for more build options.
