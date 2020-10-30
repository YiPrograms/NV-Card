# NV-Card
A script to switch NVIDIA graphics card

## Installation

### Manual

- For bbswitch method
```shell
git clone https://github.com/YiPrograms/NV-Card.git
sudo cp NV-Card/card /usr/local/bin
```

- For kernel PM method
```shell
git clone https://github.com/YiPrograms/NV-Card.git
cd NV-Card
git checkout nv-card-pm
sudo cp card /usr/local/bin
```

### Arch Linux

AUR package is available [here](https://aur.archlinux.org/packages/nv-card/) and [here](https://aur.archlinux.org/packages/nv-card-pm/)

`yay nv-card` for bbswitch version, or
`yay nv-card-pm` for kernel PM version


## Usage

`card on` : Turn the graphics card on

`card off` : Turn the graphics card off

`card run` : Turn the card on and turn it off after keyboard interruption

`card stat` : Show graphics card status

`card watch` : Monitor graphics card status

`card display` : Start external display

`card [command]` : Run [command] using optirun

## Special Thanks

ON/OFF script from [nvidia-xrun](https://github.com/Witko/nvidia-xrun)
