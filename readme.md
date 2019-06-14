# Simple paint program for STM32CubeF7 microcontroller.

After connecting to the server using the lwip library, the client draws together with all other users on shared screen.
TCP socket is used in two-way communication with the server.

* use of 2 display layers provided by the system for ui and image to minimize draw cost
* minimal ui with custom made buttons: hsl color palette, changing size, clean
* lwip

You can find [server files here](https://github.com/Pan-Maciek/STM32Cube-Paint-server).