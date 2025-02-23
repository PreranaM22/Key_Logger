# Simple Python Keylogger

A basic keylogging utility built with Python using the `pynput` library. This program logs keyboard inputs to a text file with timestamps.

## ⚠️ Important Notice

This tool is intended for **educational purposes only**. Keyloggers can be misused to capture sensitive information without consent. Always:

- Obtain explicit permission before monitoring any device

- Follow local laws and regulations regarding monitoring software

- Use responsibly and ethically

## Features

- Logs all keyboard inputs with timestamps

- Creates a log file in the same directory as the script

- Simple and lightweight implementation

## Prerequisites

- Python 3.x

- pynput library

## Installation

1\. Clone this repository:

```bash

git clone https://github.com/PreranaM22/Key_Logger.git

```

2\. Install the required package:

```bash

pip install pynput

```

## Usage

1\. Run the script:

```bash

python keylogger.py

```

2\. The program will start logging keystrokes to `keylog.txt` in the same directory

3\. To stop the program, press `esc`

## Output Format

The keystrokes are logged in the following format:

```

2025-02-23 10:30:45,123: Key.shift

2025-02-23 10:30:45,234: 'a'

```

## Project Structure

```

.

├── keylogger.py

├── keylog.txt

└── README.md

```

## Stopping the Program

- Press `esc` in the terminal

- Close the terminal window

- Use Task Manager/Activity Monitor to end the Python process

## Contributing

Feel free to fork this project and submit pull requests for any improvements.

## Disclaimer

The author takes no responsibility for any misuse of this software. This tool should only be used for educational purposes or on systems you own or have explicit permission to monitor.

## References

## References

This project was inspired by/adapted from [Creating a Python Keylogger in 10 Lines of Code](https://www.askpython.com/python/examples/python-keylogger) by [Debjeet Banerjee]
