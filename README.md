# IBM System/23 Datamaster ROM adapters

The mask ROMs in the System/23 fail often. They can easily be replaced with Motorola MCM68764 or 68766-35 EPROMs, but those are hard to find and harder to find a programmer for.

Most current, cheap USB programmers will program a 28C64 EEPROM chip so these adapters were whipped up to allow for direct plug-in replacement of defective mask ROMs.

I made two different types. One where the PLCC chip can be soldered directly to the DIP adapter PCB and one where the chip can be inserted into a PLCC socket.

Program the chip before placing it in or on either adapter.

# Do not use .100 headers on these

The .100 headers will not fit machine pin sockets and WILL damage DIP sockets. Solder machine pin headers onto the DIP adapter and the adapter can be plugged in without fear of damaging sockets on the System/23.
