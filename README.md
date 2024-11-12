# Tmux Configurations for a Personalized and Beautiful Terminal Setup

This repository contains my customized `tmux` configuration files, scripts, and plugins for creating a visually appealing and highly functional terminal setup. It includes dynamic CPU, memory, and disk monitoring integrated into the `tmux` status bar.

## Features

- **Dynamic System Monitoring**: Real-time CPU, memory, and disk usage displayed in the `tmux` status bar.
- **Nerd Font Icons**: Visually enhanced with icons for better readability.
- **Custom Layouts**: Left and right status bar configurations for better organization.
- **Simple Setup**: Easy to install and configure for personal use.

## Screenshots

![Status Bar Screenshot](/images/tmuxstatusbaronly.png)
![WholeTerminal View](/images/StatusBarTmux.png)

## Installation

### Prerequisites

- `tmux` installed on your system.
- A Nerd Font (e.g., Hack Nerd Font) installed and configured in your terminal.

### Steps

1. Clone this repository:

   ```bash
   git clone git@github.com:Rehjii-Martin/tmux-config.git
   cd tmux-config

   ```

2. Copy the .tmux.conf file to your home directory

```bash
cp .tmux.conf ~/

```

3. Copy the plugins/ folder to the appropriate directory

```bash
cp -r plugins/ ~/.tmux/plugins/

```

4. Reload tmux

```bash
tmux soure-file ~/.tmux.conf
```

5. Finish and run tmux!

```bash
tmux
```
