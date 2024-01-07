# Eletechsup R428A01 1 Channel RS485 Relay

An alternative way to open the box is to inject Modbus over RS-485.

## PDF files

PDF files came with it, I claim no ownership, only storing them here for
future reference.

## Activation

Relay Slave ID is 0x1

You want to Write Single Register (0x6)

You want to write 0x100 to Address 0x1 to Open

You want to write 0x200 to Address 0x1 to Close
