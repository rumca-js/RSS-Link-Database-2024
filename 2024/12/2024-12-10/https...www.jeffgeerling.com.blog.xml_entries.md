# Source:Jeff Geerling's Blog, URL:https://www.jeffgeerling.com/blog.xml, language:en

## Raspberry Pi 500 uses QMK Firmware for built-in keyboard
 - [https://www.jeffgeerling.com/blog/2024/raspberry-pi-500-uses-qmk-firmware-built-keyboard](https://www.jeffgeerling.com/blog/2024/raspberry-pi-500-uses-qmk-firmware-built-keyboard)
 - RSS feed: $source
 - date published: 2024-12-10T15:52:00+00:00

<span class="field field--name-title field--type-string field--label-hidden">Raspberry Pi 500 uses QMK Firmware for built-in keyboard</span>

            <div class="clearfix text-formatted field field--name-body field--type-text-with-summary field--label-hidden field__item"><p>I mentioned in my <a href="https://www.jeffgeerling.com/blog/2024/pi-500-much-faster-lacks-m2">Pi 500 review</a> Raspberry Pi is dogfooding their own microcontroller in the new Pi 500. An RP2040 sits next to the keyboard ribbon cable connector, and interfaces it through a USB port directly into the RP1 chip:</p>

<p><img width="700" height="auto" class="insert-image" src="https://www.jeffgeerling.com/sites/default/files/images/pi-500-rp2040-keyboard-qmk.jpg" alt="Raspberry Pi 500 PCB with RP2040 for keyboard input"></p>

<p>In good news for keyboarding enthusiasts, the RP2040 seems to be flashed with the open-source <a href="https://github.com/raspberrypi/QMK">QMK ('Quantum Mechanical Keyboard') Firmware</a>. 

