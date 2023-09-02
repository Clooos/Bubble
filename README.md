# Bubble
A dark minimalist theme with a mobile first approach for Home Assistant

[![Stars](https://img.shields.io/github/stars/clooos/Bubble)](#) [![Last commit](https://img.shields.io/github/last-commit/clooos/Bubble)](#) [![Reddit Profile](https://img.shields.io/badge/Reddit-My%20stuff-orange?logo=reddit)](https://www.reddit.com/user/Clooooos/submitted/) [![Buy me a beer](https://img.shields.io/badge/Buy%20me%20a-beer-yellow?logo=buy-me-a-coffee)](https://www.buymeacoffee.com/clooos)

Based on Noctis theme from aFFekopp

With card-mod installed you got this features:

- A mobile view on desktop (like on the screenshot and you need to set your view in subview mode)
- No header on mobile


<img width="1423" alt="Bubble Theme" src="https://github.com/Clooos/Bubble/assets/36499953/22ddbbfd-1723-4a88-834f-91bf23ba044a">

## Installation

### Without HACS

1. Download this file: [bubble-card.js](https://raw.githubusercontent.com/Clooos/Bubble/main/bubble.yaml)
2. Add this file into a new folder named `bubble` in the `<config>/themes/` folder
3. In your configuration.yaml add this: 
```yaml
frontend:
  themes: !include_dir_merge_named themes
```
4. Save and restart Home Assistant
5. Now go to your personal account settings and select Bubble as your theme

### With HACS

1. Download HACS following the instructions on [https://hacs.xyz/docs/setup/download](https://hacs.xyz/docs/setup/download/)
2. Proceed to the initial configuration following the instructions on [https://hacs.xyz/docs/configuration/basic](https://hacs.xyz/docs/configuration/basic)
3. On your sidebar go to `HACS` > `Integrations`
4. click on the icon at the right top corner then on `Custom repositories`
5. For the repository add this: `https://github.com/Clooos/Bubble-Card`
6. For the category select `Theme` then click `Add`
7. Now click on `Bubble` then on the `Dowload` button
8. In your configuration.yaml add this: 
```yaml
frontend:
  themes: !include_dir_merge_named themes
```
9. Save and restart Home Assistant
10. Now go to your personal account settings and select Bubble as your theme
