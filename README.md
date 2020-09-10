# UDP Flood

**@Vexvain**

-----------------------------------------

Take down a wifi network/device by flooding it with UDP packets. :) 

# Compile

`$ gcc -o udp-flood udp-flood.c`

# Run

    $ ./udp-flood --target/-T (TARGET IP)   --duration/-D (DURATION IN SECONDS)    --port/-P (TARGET PORT NO.)

**EXAMPLE:** 

    $ ./udp-flood --target 1.2.3.4
