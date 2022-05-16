## Windows 10 Fonts for Linux
All fonts from Win10_20H2_English_x64.iso

### Installation Guide
Copy the code and paste it to your terminal:
```console
git clone https://github.com/adtitas/win10-fonts-for-linux.git && sudo mkdir -p /usr/share/fonts/win10-fonts && sudo cp -n -r WindowsFonts/. /usr/share/fonts/win10-fonts/ && sudo chmod 644 /usr/share/fonts/win10-fonts && fc-cache
```
### Notes
* If `git` isn't installed on your system, you may need to install it. Visit [here](https://git-scm.com/download/linux).
```
