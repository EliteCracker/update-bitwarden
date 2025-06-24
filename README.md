# Update Bitwarden's AppImage
![Static Badge](https://img.shields.io/badge/WOO-HOO-blue)  
Bash script that updates the Bitwarden AppImage.  
I hate the fact that the Arch Linux [bitwarden](https://archlinux.org/packages/extra/x86_64/bitwarden/) package is out of date. I made my own script to update the .AppImage file itself in response.

## Requirements
- jq
- openssl
- An already downloaded [Bitwarden .AppImage](https://bitwarden.com/download/)  
To install: `sudo pacman -S jq openssl`


## Usage
`./update-bitwarden <Bitwarden AppImage>`

## Changelog
See the [changelog](CHANGELOG) here.

## License
See the [license](LICENSE) here.
