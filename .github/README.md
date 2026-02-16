<div align="center"><h2>more like gaybar lmao</h2></div>

This is my personal waybar configuration in calOS, forked over from the great mechabar (https://github.com/sejjy/mechabar)

<p align="center">
<img width="3440" height="424" alt="2026-02-10-200355_hyprshot" src="https://github.com/user-attachments/assets/0fdb5148-0bb3-4575-ad73-1d752d0aa1b7" />
<img width="3440" height="349" alt="image" src="https://github.com/user-attachments/assets/3b6606c7-3fbd-4590-8b2a-bee359ff13d6" />
<img width="3440" height="658" alt="2026-02-10-200412_hyprshot" src="https://github.com/user-attachments/assets/73e72b62-8d04-4900-b7bd-cffc15c7ab8f" />
<img width="3440" height="560" alt="2026-02-10-200436_hyprshot" src="https://github.com/user-attachments/assets/9628a407-6bf5-4298-a553-b2b51b22fe6e" />
</p>

### Features

* Integrates with Walker via the top left (to launch system settings) and the middle (to launch the system applications).
* The middle of the waybar helps monitor your system specs (such as temperature, RAM, CPU usage, etc.)
* Your right portion of the waybar interacts with audio (play, pause, next, volume control) and utilizes bluetui + impala for connnectivity controls.
* A system update script lives in the top right as well, click on it to check for updates. Will periodically browse pacman repos + AUR to check if updates are available.
* its a fucking waybar skin why are you looking at the features list lmao

### How 2 Install

Just cloning the repo is enough for basic functionality. Install `gum` if you want to utilize the system update script. Pay close attention to styles/waybar.css as those are your main accent colors (for the dividers). Open up the `config.jsonc` file and edit what applications/binaries you wish to run on click/which terminal you want to utilize. There are some defaults for my own OS on their as well that can be easily removed (such as the gamemode script). Enjoy!
