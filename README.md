# Personalized Dmenu Fork

This repository contains a personalized fork of Dmenu, a dynamic menu for X, with patches applied to enhance its functionality and appearance.

Feel free to explore and adapt this customized Dmenu fork to suit your own preferences and requirements.

## Screenshot

![dmenu](./screenshot.png)

## Applied Patches

- `xresources`: Enables reading color settings from the X resources database (xrdb).
- `center`: Centers the dmenu window on the screen.
- `grid`: Implements a grid layout for displaying menu options.
- `gridnav`: Adds navigation support for selecting menu options using arrow keys in the grid layout.
- `border`: Adds a border around the dmenu window.

## Installation

1. Clone the repository to your local machine.
   ```shell
   git clone https://github.com/AkamQadiri/dmenu
   ```

2. Compile and install Dmenu by running the following command within the cloned repository:
   ```shell
   sudo make clean install
   ```
