## Installation

1. Clone this repository

    ```bash
    git clone "https://github.com/{{repository.publisher}}/{{repository.repo}}.git" ./wezterm
    cd ./vscode
    ```

2. Set `color_scheme_dirs` in your `wezterm.lua`

    Refer to [this](https://wezfurlong.org/wezterm/config/appearance.html#defining-a-color-scheme-in-a-separate-file) official configuration

3. Set `color_scheme` to your preferred flavor.

    ```lua
    -- (e.g. `oneiroi dream`)
    color_scheme = "oneiroi dream",
    ```
