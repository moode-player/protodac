# ProtoDAC TDA1387 X8

The ProtoDAC TDA1387 X8 is a DIY DAC based on the vintage Philips TDA1387 multibit DAC chip in an eight chip module as pictured below. The chips are configured in parallel with decoupling capacitors and pin 7 capacitors on the underside of the module.

The module is designed as a direct plug in replacement for the famous TDA1541, which is now difficult to obtain. The TDA1541 was a flagship Philips multibit 16 bit DAC in a 28 pin Dual In-line Package (DIP), and is older and more complex. The TDA1387 is a later development multibit DAC with current output, and simplified having only 8 pins.

The TDA1387 is a very interesting 16-bit design and represents the end of the multibit DAC era. It uses continuous calibration of the five most significant bit current sources, so it has 32 current sources and one spare source. Philips multibit DACs are also unique in that they do not use resistors like some other DACs, but instead use active devices to generate the currents.

The ProtoDAC is one of the easiest NOS DAC's to build. The number of components is low and the circuit design is simple since the TDA1387 directly uses I2S from the Raspberry Pi as input and passive I/V is used for the output stage.

Most importantly, the sound quality of the finished DAC is excellent, especially when using premium components.

By: @hifinet (c) 2023

### Disclaimer ###

The software and other materials in this repository are distributed under the [GNU GENERAL PUBLIC LICENSE Version 3](https://raw.githubusercontent.com/moode-player/protodac/main/LICENSE) which includes the following disclaimer:

>15. Disclaimer of Warranty.
>
>THERE IS NO WARRANTY FOR THE PROGRAM, TO THE >EXTENT PERMITTED BY
>APPLICABLE LAW.  EXCEPT WHEN OTHERWISE STATED IN WRITING THE COPYRIGHT
>HOLDERS AND/OR OTHER PARTIES PROVIDE THE PROGRAM "AS IS" WITHOUT WARRANTY
>OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING, BUT NOT LIMITED TO,
>THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
>PURPOSE.  THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF THE PROGRAM
>IS WITH YOU.  SHOULD THE PROGRAM PROVE DEFECTIVE, YOU ASSUME THE COST OF
>ALL NECESSARY SERVICING, REPAIR OR CORRECTION.
>
>16. Limitation of Liability.
>
>IN NO EVENT UNLESS REQUIRED BY APPLICABLE LAW OR AGREED TO IN WRITING
>WILL ANY COPYRIGHT HOLDER, OR ANY OTHER PARTY WHO MODIFIES AND/OR CONVEYS
>THE PROGRAM AS PERMITTED ABOVE, BE LIABLE TO YOU FOR DAMAGES, INCLUDING ANY
>GENERAL, SPECIAL, INCIDENTAL OR CONSEQUENTIAL DAMAGES ARISING OUT OF THE
>USE OR INABILITY TO USE THE PROGRAM (INCLUDING BUT NOT LIMITED TO LOSS OF
>DATA OR DATA BEING RENDERED INACCURATE OR LOSSES SUSTAINED BY YOU OR THIRD
>PARTIES OR A FAILURE OF THE PROGRAM TO OPERATE WITH ANY OTHER PROGRAMS),
>EVEN IF SUCH HOLDER OR OTHER PARTY HAS BEEN ADVISED OF THE POSSIBILITY OF
>SUCH DAMAGES.

This means that the user of this software is responsible for any damage resulting from its use.
It does not matter if the damage is caused by incorrect usage or a bug in the software.
