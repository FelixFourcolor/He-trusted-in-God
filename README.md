# He trusted in God
Play Handel's Messiah - "He trusted in God" in Minecraft's noteblocks.

## Requirements
Minecraft java 1.18+

## Installation 
Download and copy the World folder into your saves, or

### Build from source
Build requirements: git, python 3.10+, pip.

1. Create a new Minecraft world (java 1.18+), preferably (for performance) in peaceful mode, superflat type, and without generated structures. 

2. Save and exit the world.

3. On the command line:

```
# install dependencies
pip install --upgrade pip
pip install amulet-core

# clone and enter this repo
git clone --recurse-submodules https://github.com/FelixFourcolor/He-trusted-in-God.git
cd He-trusted-in-God

# generate
python noteblock-generator/generate.py src.json [path to your minecraft world]
```

Checkout [noteblock-generator](https://github.com/FelixFourcolor/noteblock-generator)'s documentation, which explains how this program works. Also checkout [Amulet-Core](https://github.com/Amulet-Team/Amulet-Core), which this program heavily relies upon.

## License
Do whatever you want.