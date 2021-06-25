# rarick/tmux-airline

A tmux airline theme which uses the terminal color scheme

## Installation

1. Install using tpm.

    ```tmux
    set -g @plugin 'rarick/tmux-airline'
    ```

## Manual Installation

1. Clone this repository

    ```sh
    git clone --depth=1 https://github.com/rarick/tmux-airline.git
    ```

1. Add the following to your `tmux.conf`

    ```tmux
    run-shell '. /path/to/rarick/tmux-airline/airline.tmux'
    ```
