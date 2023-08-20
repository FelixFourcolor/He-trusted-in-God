# He trusted in God
"He trusted in God" in Handel's Messiah,  arranged for Minecraft's noteblocks.

Recording: https://www.youtube.com/watch?v=jQLKgxHWafE

## Arrangement
Noteblock's capabilities are quite limited, so lots of compromises had to be made.

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

A few notes are (hopefully inconspicuously) changed in order to fit the their instrument's range.

## Play requirement
Minecraft java 1.18+

## Easy install 
Copy the `World` folder into your saves. 

To obtain the folder, you may clone the repo or use third-party tools such as [Down-Git](https://minhaskamal.github.io/DownGit) to download it.

## Build from source
### Build requirements
* python 3.10+
* pip

### Overview of the build process
The structure is auto-generated using [noteblock-generator](https://github.com/FelixFourcolor/noteblock-generator). The program takes `src.json` which defines the composition, and generates the structure inside an existing Minecraft world.

### Step-by-step guide

1. Install the latest version of [noteblock-generator](https://github.com/FelixFourcolor/noteblock-generator):
    ```
    pip install --upgrade noteblock-generator
    ```
    Configure your PATH so that `noteblock-generator` is executable on the command line.

2. Obtain `src.json`. You may clone the repo or download just that file.

3. Obtain a world in Minecraft java 1.18+. You may use your existing world or create a new one. 


4. If you are inside the world, exit it first. Then,
    ```
    noteblock-generator --clear [path to src.json] [path to minecraft world]
    ```
    (See [noteblock-generator](https://github.com/FelixFourcolor/noteblock-generator)'s documentation for explanation and more build options.)

## License
Do whatever you want.
