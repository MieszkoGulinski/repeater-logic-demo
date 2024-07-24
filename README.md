# Demo of logic for controlling an amateur radio repeater.

This repository contains a simple demonstration of logic for controlling an amateur radio repeater. The logic in the demo is written in JavaScript and the demo is running as a web page, but for an actual repeater, the logic would be implemented in a microcontroller.

Actually, this is not only a demo - running this code was used to fix bugs and refine the logic before implementing it in a microcontroller. For example, running the code allowed me to add two trailing zeros in the Morse code callsign lookup table, which was necessary to make the logic work correctly.

To see how the code is actually implemented, look at the `script` tag in the page source.

The only other file in this repository is `docs/index.html`, which contains the demo. You can view the demo at https://mieszkogulinski.github.io/repeater-logic-demo/.
