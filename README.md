# Shell Configuration Files

This repository contains my personal shell configuration files and useful 
aliases for bash. These files help customize and enhance the shell environment
for betterproductivity and user experience.

## Contents

### `bashrc`
The main bash configuration file that includes:
- Custom prompt with timestamp, username, hostname, working directory, git
  status, and exit status
- History settings
- Color support for various commands
- Integration with zoxide for smarter directory navigation
- Python environment activation
- Various shell options and settings

### `bash_aliases`
Contains useful command aliases, including:
- `transpose`: A utility to transpose text data (useful for working with tabular
  data)

## Features

- **Custom Prompt**: Shows date, time, user@host, working directory, git status,
  and command exit status
- **Enhanced Navigation**: Integration with zoxide for smarter directory
  navigation
- **Python Environment**: Automatic activation of Python virtual environment
- **Useful Aliases**: Custom commands to simplify common tasks

## Installation

To use these configuration files:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/shell-stuff.git
   ```

2. Create symbolic links to your home directory:
   ```bash
   ln -s ~/shell-stuff/bashrc ~/.bashrc
   ln -s ~/shell-stuff/bash_aliases ~/.bash_aliases
   ```

3. Source the new configuration:
   ```bash
   source ~/.bashrc
   ```

## Requirements

- bash shell
- zoxide (for enhanced directory navigation)
- Python virtual environment (if you want to use the Python environment feature)

## License

This project is open source and available under the MIT License. 
