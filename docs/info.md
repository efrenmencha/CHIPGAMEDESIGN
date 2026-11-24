<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

GAME RULES

    The ball is an LED that advances one position on each clock edge (4 Hz).

    To return it, the player must hold down their button when the ball reaches their end LED.

    You lose the point if you don’t respond in time or if you press too early (fault), with the ball 2 or more LEDs away.

    After each point, the display shows the scoring player’s points (decimal point on = Player B) for 2 s, and then the player who lost serves automatically.

    The first player to reach 5 points wins; on the next serve, the score returns to 0
## How to test

Key A (or blue button): Player A; their side is LED0 (left).

Key L (or red button): Player B; their side is LED7 (right).

Key R: reset.

Key S: step-by-step clock advance (with the slide switch in manual mode).

## External hardware

4 Khz External clock
Three push button for inputs
Eight LEDS output
