Application + Board definition repository
#########################################

Overview
********

This is a copy of Zephyr's hello_world app with an out of tree board.

The board's name is "con_a", but it's just a copy/paste of the nrf52dk_nrf52832
board with the name changed and documentation directory removed.

Building and Running
********************

west build -b con_a .

