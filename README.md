# flabbergast's kicad files

## kb45p

This is a PCB for a 45% keyboard. Supports ALPS and Cherry MX switches. No LEDs, only one SMT LED on the front bottom side. The supported layouts are  [this](http://www.keyboard-layout-editor.com/##@@=Tab&=Q&=W&=E&=R&=T&=Y&=U&=I&=O&=P&=%7C%0A%5C&=Back%3Cbr%3ESpace%3B&@_w:1.25%3B&=Ctrl&=A&=S&=D&=F&=G&=H&=J&=K&=L&=%2F:%0A%2F%3B&_w:1.75%3B&=Enter%3B&@_w:1.75%3B&=Shift&=Z&=X&=C&=V&=B&=N&=M&=%3C%0A.&=%3E&_w:1.25%3B&=Shift&=Fn%3B&@_x:1.25%3B&=Alt&_w:1.25%3B&=Cmd&_a:7&w:2.25%3B&=&_a:7&w:2.75%3B&=&_a:4&w:1.25%3B&=Cmd&=Alt&=Meta) and [this](http://www.keyboard-layout-editor.com/##@@=Tab&=Q&=W&=E&=R&=T&=Y&=U&=I&=O&=P&=%7C%0A%5C&=Back%3Cbr%3ESpace%3B&@_w:1.25%3B&=Ctrl&=A&=S&=D&=F&=G&=H&=J&=K&=L&=%2F:%0A%2F%3B&_w:1.75%3B&=Enter%3B&@_w:1.75%3B&=Shift&=Z&=X&=C&=V&=B&=N&=M&=%3C%0A.&=%3E&_w:1.25%3B&=Shift&=Fn%3B&@_x:1.25%3B&=Alt&_w:1.25%3B&=Cmd&_a:7&w:6.25%3B&=&=Alt&=Meta).

The controller MCU is STM32F042K6T7 - 32kB flash, 6kB RAM, DFU bootloader in ROM, LQFP-32 package. The BOOT0 pin for entering the bootloader on power up is brought out to a pushbutton on the bottom side of the PCB.
