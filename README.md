# Android Studio Flatpak

🚨 Warning: This is an unofficial Flatpak build of Android Studio, generated from the official Google-built zip file [here](https://developer.android.com/studio/archive).

## Usage

Most functionality works out of the box, though please note that flatpak runs in an isolated environment and some work is necessary to enable those features.

### Execute commands in the host system.

To execute commands on the host system, run inside the sandbox:

`$ flatpak-spawn --host <COMMAND>`
