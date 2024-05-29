# mac-fragment-scanner

This script is designed to test various configurations of the Xray fragmentation settings on macOS.

## Installation

1.  **Install the `Homebrew`**:
    ```sh
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    ```
   
2. **Install the `powershell` using `Homebrew`**:
   ```sh
    brew install --cask powershell
    ```

3. **Get the lastest `xray` core**:
   ```sh
    https://github.com/XTLS/Xray-core/releases
    ```
   
4. **Ensure the `xray` executable is in the directory**:
    ```sh
    chmod +x ./xray
    ```

## Usage

1. **Open PowerShell**:
    ```sh
    pwsh
    ```

2. **Run the script**:
    ```sh
    ./mac2.ps1
    ```


If you got an error that doesn't let xray run, go to settings, privacy and allow it:

![Screenshot of a common error](xrayblocked.png)


