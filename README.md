# NV-Card
A script to switch NVIDIA graphics card using bbswitch

## Installation

```shell
git clone https://github.com/YiPrograms/NV-Card.git
sudo cp NV-Card/card /usr/local/bin
```

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