# Installation

🐸TTS supports python >=3.9 <3.12.0 and was tested on Ubuntu 20.04 and 22.04.

## Using `pip`

`pip` is recommended if you want to use 🐸TTS only for inference.

You can install from PyPI as follows:

```bash
pip install coqui-tts  # from PyPI
```

Or install from Github:

```bash
pip install git+https://github.com/eginhard/coqui-tts  # from Github
```

## Installing From Source

This is recommended for development and more control over 🐸TTS.

```bash
git clone https://github.com/eginhard/coqui-tts
cd coqui-tts
make system-deps  # only on Linux systems.
make install
```

## On Windows
If you are on Windows, 👑@GuyPaddock wrote installation instructions
[here](https://stackoverflow.com/questions/66726331/) (note that these are out
of date, e.g. you need to have at least Python 3.9)
