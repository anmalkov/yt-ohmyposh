# Oh My Posh theme and configuration
In this repo you can find my Oh My Posh theme and configuration.

## Installation

1. Copy file `themes/agnoster.anmalkov.omp.json` to your Oh My Posh themes folder. You can find it by running command `echo $env:POSH_THEMES_PATH`.
2. Add a line or update your PowerShell profile with the code below. You can find your PowerShell profile by running command `echo $PROFILE`.

    ```powershell
    oh-my-posh init pwsh --config $env:POSH_THEMES_PATH\agnoster.anmalkov.omp.json | Invoke-Expression
    ```

3. Restart your terminal.
