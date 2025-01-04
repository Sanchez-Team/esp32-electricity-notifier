
[![MIT License](https://img.shields.io/badge/license-CC--BY--NC--SA--4.0-lightgrey)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.en)
[![Code Size in Bytes](https://img.shields.io/github/languages/code-size/Sanchez-Team/esp32-electricity-notifier)](https://github.com/Sanchez-Team/esp32-electricity-notifier)


# Electrical outage notifier using ESP32, SIM800L and Telegram

This project is to be used in enviorments, where the user isn't always there, but, needs to know about status of electrical network there. Currently, it only supports *Telegram HTTP API*, yet, support for other APIs are planned.

## Feedback

If you have any feedback, please reach out to us at alexvolkov@email.cz

## Run Locally

### Flashing your ESP32 with micropython firmware
Firstly, if you haven't flashed your ESP32 with micropython firmware - you should do that first.
To do that, you need to go on [this website](https://micropython.org/download/) and look for your exact model, **and follow instructions carefully. Nobody is responsible if you brick your ESP32.**

After you've flashed your ESP32, we can continue.

### Downloading Thonny

This tutorial is using [Thonny](https://thonny.org/) to edit the programme, and, flash it to the board.
However, using Thonny isn't enforced, therefore, you can and absolutely *should* try out/use different ways of flashing software onto the board.

### Flashing programm onto the ESP32

Firstly, use those commands to clone the project and go to the folder of the project.

```bash
  git clone https://github.com/Sanchez-Team/esp32-electricity-notifier
  cd esp32-electricity-notifier
```

Then, open Thonny, click on the bottom-right corner of the program (Should say something among the lines of `Local Python 3 * /usr/bin/python3`), after that, in the field `Which kind of interpreter should Thonny use for running your code?` select `Micropython (ESP32)` and click OK.

## License

This work is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1)

