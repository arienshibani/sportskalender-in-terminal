# Sportskalender Zsh Plugin

This is a Zsh plugin that provides commands to display the highlight page or football page from VGs sportskalender in the terminal. The plugin is based on the [sportskalender](https://www.vg.no/sport/kalender) from VG.

<img width="758" alt="image" src="https://github.com/hbleie/sportskalender-in-terminal/assets/92336221/480a8008-32ea-4141-b2ff-1acb1e6795dd">


## Installation

### Oh My Zsh

1. Clone this repository into `$ZSH_CUSTOM/plugins` (by default `~/.oh-my-zsh/custom/plugins`)

2. Add the plugin to the list of plugins for Oh My Zsh to load
    plugins=(... sportskalender-in-terminal)

3. Start a new terminal session.

### Antigen

1. Add `antigen bundle johannsl/sportskalender-in-terminal` to your `.zshrc` with your other bundle commands.

2. Start a new terminal session.

### Zgen

1. Add `zgen load johannsl/sportskalender-in-terminal` to your `.zshrc` in the same function you're doing your other `zgen load` calls in.

2. Start a new terminal session.

### Manual

1. Clone this repository somewhere on your machine.

2. Source the file `sportskalender-in-terminal.plugin.zsh` in your `.zshrc` file.

    ```zsh
    source /path/to/sportskalender-in-terminal.plugin.zsh
    ```

3. Start a new terminal session.

## Usage

### `høydepunkter`

Displays the highlight page from VGs sportskalender in the terminal.

Run the command `sport høydepunkter` to display the highlight page.

### `fotball`

Displays the football page from VGs sportskalender in the terminal.

Run the command `sport fotball` to display the football page.
