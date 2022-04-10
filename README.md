# corewar (graphical virtual machine)

## Subject

Corewar consists of pitting little programs against one another in a virtual machine.

The goal of the game is to prevent the other programs from functioning correctly by using all available
means.

This program is a graphical interface for the virtual machine.

## Use case

The graphical interface is made to support it and simplify the test phase when implementing a new warrior.

It allows you to see all the byte values in hexadecimal, the warriors defined by a color and processes highlighted in white etc...

To see a demonstration: https://youtu.be/h-L2ckOpVg8

## Execute

You just have to compile with `make` and then execute the program like that:\
`./vm warrior/42.cor warrior/abel.cor warrior/bill.cor warrior/pdd.cor`

You have a bunch of warriors in `warriors` directory.

## Help

keyboard shortcut:

| Shortcuts | Description |
| ------ | ------ |
| Space bar | Pause the game |
| key D | slow down the game / speed it up again |
| Key Q | Exit the game |
