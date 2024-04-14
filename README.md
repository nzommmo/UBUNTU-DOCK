<p align="center">
  <img src="/preview/Screenshot from 2024-04-14 18-45-49.png" alt="Header Image">
</p>

# GNOME Dash to Dock Configuration in Ubuntu

This repository contains configuration settings for the GNOME Dash to Dock extension to customize its behavior and appearance in Ubuntu

## Table of Contents

- [Description](#description)
- [Settings](#settings)
- [Usage](#usage)
- [Preview](#preview)
- [Contributing](#contributing)
- [License](#license)

## Description

GNOME Dash to Dock is an extension for the GNOME Shell that allows users to customize the dock behavior and appearance. This repository provides a set of configuration settings that can be applied to the Dash to Dock extension to achieve specific customization options.

## Settings

The following settings are included in this repository:

- `extend-height`: Set to `false` to prevent the dock from extending its height to fill the available vertical space.
- `dock-position`: Set to `BOTTOM` to position the dock at the bottom of the screen.
- `transparency-mode`: Set to `DYNAMIC` to enable dynamic transparency mode for the dock.
- `dash-max-icon-size`: Set the maximum icon size for icons in the dash.
- `background-opacity`: Set the opacity of the dock background. Set to `0` for complete transparency.
- `dock-fixed`: Set to `false` to allow the dock to resize dynamically based on available space.

## Usage

To use these settings, you can apply them using the `gsettings` command-line tool. Here's an example of how to apply the settings:
Paste the script below in your system terminal.

```bash
gsettings set org.gnome.shell.extensions.dash-to-dock extend-height false
gsettings set org.gnome.shell.extensions.dash-to-dock dock-position BOTTOM
gsettings set org.gnome.shell.extensions.dash-to-dock transparency-mode DYNAMIC
gsettings set org.gnome.shell.extensions.dash-to-dock dash-max-icon-size 36
gsettings set org.gnome.shell.extensions.dash-to-dock background-opacity 0
gsettings set org.gnome.shell.extensions.dash-to-dock extend-height false
gsettings set org.gnome.shell.extensions.dash-to-dock dock-fixed false
```
## Preview
![Desktop view](/preview/Screenshot%20from%202024-04-14%2018-45-49.png)



## Contributing
Contributions to add more configuration settings or improve existing ones are welcome. Please fork the repository, make your changes, and submit a pull request.

## License
This repository is licensed under the MIT License.


