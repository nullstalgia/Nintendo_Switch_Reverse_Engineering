# My Nintendo Switch reverse engineering attempts

Basically I'm just going to dump all my discoveries here, and hopefully they would be useful to the Nintendo Switch community.

## Left Joycon PCB Layout

![Alt text](http://i.imgur.com/7Ui8lFv.jpg)

For the full-sized PDF [click here](./joycon_left_pcb.pdf).

## A few words about left Joycon PCB

* In a bizarre move Nintendo didn't use the traditional "one side pulled-up and other side to ground" way of reading buttons, instead they used a keypad configuration where buttons are arranged to rows and columns. They used the keypad scanner built-in inside the BCM20734 for reading the buttons. That means it would be extremely hard to spoof button presses for TASes and twitch-plays. Maybe pro controller is different, still need to buy one.

* Joycon runs at 1.8V
