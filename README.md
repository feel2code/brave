
# BRAVE

BRAVE is a simple command-line tool (script) for:
- easily removing audio from multiple video files at once.
- easily merge videos into one video file.

It's written in Bash shell scripting language, making it compatible with various Unix-like systems.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#Installation)
- [Usage](#Usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

BRAVE (Batch Remove Audio from Video Easily) is designed to simplify the process of batch working with multiple video files.

## Features

- Batch removal of audio from multiple video files.
- Merge several videos into one video.
- Support for various video formats.
- Lightweight and efficient, utilizing Bash scripting capabilities.
- Easy-to-use command-line interface or just click on it in GUI mode.

## Requirements

- Bash (Bourne Again SHell)
- [FFmpeg](https://www.ffmpeg.org/) (a multimedia framework to handle multimedia data)

Ensure you have both Bash and FFmpeg installed on your system before using BRAVE. 

In most popular Linux distributes and macOS Bash already installed!

## Installation

1. Clone this repository or just save it via GitHub button:
   ```bash
   git clone https://github.com/feel2code/brave.git
   cd brave

2. Make the `brave` script executable via terminal or via file properties:
   ```bash
   chmod +x brave

## Usage

1. Place BRAVE tool to the directory where the target videos exist
2. Start the BRAVE tool by clicking on it in your favorite file manager or just in terminal:
   ```bash
   ./brave
3. Select option that you need:
   ```markdown
   1) Batch remove audio from videos
   2) Merge videos into one file
   3) Quit
   ```

## Contributing
Contributions are welcome! Feel free to submit bug reports, feature requests, or pull requests on [GitHub](https://github.com/feel2code/brave).

## License
This project is licensed under the MIT License.