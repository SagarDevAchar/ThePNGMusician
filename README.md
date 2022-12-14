![image](https://user-images.githubusercontent.com/51400137/183271112-234bc214-c38f-43aa-8267-f473f56182f4.png)

[![Active Version](https://img.shields.io/badge/version-v2022.07.19-blue)](https://github.com/SagarDevAchar/ThePNGMusician/releases/download/release/The.PNG.Musician.v2022.07.19.zip)
[![GitHub issues](https://img.shields.io/github/issues/SagarDevAchar/ThePNGMusician)](https://github.com/SagarDevAchar/ThePNGMusician/issues)
[![GitHub license](https://img.shields.io/github/license/SagarDevAchar/ThePNGMusician)](https://github.com/SagarDevAchar/ThePNGMusician/blob/main/LICENSE)

<!--
<p align="center">
  <a href="https://github.com/SagarDevAchar/ThePNGMusician">
    <img align="center" src="https://img.shields.io/badge/version-v2022.07.19-blue" />
  </a>
  <a href="https://github.com/SagarDevAchar/ThePNGMusician/issues">
    <img align="center" src="https://img.shields.io/github/license/SagarDevAchar/ThePNGMusician" />
  </a>
  <a href="https://github.com/SagarDevAchar/ThePNGMusician/blob/main/LICENSE">
    <img align="center" src="https://img.shields.io/github/license/SagarDevAchar/ThePNGMusician" />
  </a>
</p>
-->

# The PNG Musician

An LSB2 Steganography Decoder which extracts and plays MP3 Audio from the PNG Images generated by [**The MP3 Photographer**](https://github.com/SagarDevAchar/TheMP3Photographer)

## About the Project

This is third part of the **Steganography Made Fun!** toolkit

The toolkit has three parts divided into three repositories:

- Part 1: [The TXT Hider](https://sagardevachar.github.io/TheTXTHider/)
- Part 2: [The MP3 Photographer](https://sagardevachar.github.io/TheMP3Photographer/)
- Part 3: [The PNG Musician](https://sagardevachar.github.io/ThePNGMusician/) (This Repository)

## Repository Structure

- `bin\` : Contains the `mpg123` binary for Audio Playback
- `SRC\` : Contains the Steganographically Encoded PNG Files
- `LICENSE` : GNU GPL v3.0 License for [The PNG Musician](https://github.com/SagarDevAchar/ThePNGMusician)
- `README.md` : Here you are!
- `install_requirements.bat` : Installs the necessary package requirements using `pip` (Requires `pip` access in `PATH`)
- `The PNG Musician.py` : Source Code

## Usage Instructions

1. Just let things be where they are (relatively)
1. Run `The PNG Musician.py` using the IDE of your choice or via CMD using the `python "The PNG Musician.py"` command
1. Witness the magic (well, not really :P)

Place the Custom PNG files generated by [**The MP3 Photographer**](https://github.com/SagarDevAchar/TheMP3Photographer) in the `SRC\` folder to play it in [**The PNG Musician**](https://github.com/SagarDevAchar/ThePNGMusician)

## Requirements

- **Operating System:** Windows
- **Python Version:** 3.5+
- **Packages:** [TQDM](https://tqdm.github.io/), [NumPy](https://numpy.org/), [OpenCV](https://opencv.org/)

You can install the requirements by running the `install_requirements.bat`. You can always create a virtual environment to prevent your version critical installations from being modified (You need to switch to the virtual environment before running the batch file)

## Disclaimer

I do not own any rights to the image or music in this repository. All rights are reserved by the respective artists and record labels

## Acknowledgements and References

- ASCII Art by: [TextKool](https://textkool.com/en)
- Quickstart: [Secrets Hidden in Images (Steganography) - Computerphile](https://youtu.be/TWEXCYQKyDc)
