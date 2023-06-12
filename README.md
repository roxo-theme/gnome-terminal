<div align="center">

# Roxo for GNOME terminal

![gnometerminal](https://img.shields.io/static/v1?message=GNOME%20terminal&logo=gnometerminal&color=120d17&label=%20%20)
[![License: MIT](https://img.shields.io/badge/License-MIT-97ca39.svg)](https://opensource.org/licenses/MIT)

<img src="./assets/gnome-terminal-preview.png" />

</div>

## Installation

- Get [roxo-theme.dconf](https://raw.githubusercontent.com/roxo-theme/gnome-terminal/main/roxo-theme.dconf)
  and save it to a directory, e.g. `$HOME/Downloads/roxo-theme.dconf`.
- Open GNOME terminal and execute the command:

  ```sh
  dconf load /org/gnome/terminal/legacy/profiles:/ < $HOME/Downloads/roxo-theme.dconf
  ```

- Open _Preferences_ and select **Roxo Theme** profile.
