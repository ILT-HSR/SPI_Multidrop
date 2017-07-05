# ![SPICE Logo](/SPICE_064.png) SPI_Multidrop

SPI_Multidrop is an implemented SiLA ServiceProvider based on [SPICE](https://github.com/ILT-HSR/SPICE).

## Supported Multidrops
* Multidrop Combi
* Multidrop Micro
* Multidrop 384
* Multidrop DW

## Provided Functionality
* Flexible command set: At startup the implemenation detects the connected Multidrop version and provides an adjusted command set.
* Connection over RS232
* Intelligent error-handling: providing helpful continuation tasks.
* WSDiscovery (Type: "SiLADevice", no Scope)

## SiLAVersion
SPI_Multidrop v2.0: based on SPICE 1.0.x, implements SiLA DCIS 1.3.08 specification

## License
SPI_Multidrop is provided under the Boost Software License. SPI_Multidrop is not and has no intention to be part of the Boost
libraries. It just uses this very open license that encourages both commercial and non-commercial use.

> Boost Software License - Version 1.0 - August 17th, 2003
>
> Permission is hereby granted, free of charge, to any person or organization
> obtaining a copy of the software and accompanying documentation covered by
> this license (the "Software") to use, reproduce, display, distribute,
> execute, and transmit the Software, and to prepare derivative works of the
> Software, and to permit third-parties to whom the Software is furnished to
> do so, all subject to the following:
>
> The copyright notices in the Software and this entire statement, including
> the above license grant, this restriction and the following disclaimer,
> must be included in all copies of the Software, in whole or in part, and
> all derivative works of the Software, unless such copies or derivative
> works are solely in the form of machine-executable object code generated by
> a source language processor.
>
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
> IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
> FITNESS FOR A PARTICULAR PURPOSE, TITLE AND NON-INFRINGEMENT. IN NO EVENT
> SHALL THE COPYRIGHT HOLDERS OR ANYONE DISTRIBUTING THE SOFTWARE BE LIABLE
> FOR ANY DAMAGES OR OTHER LIABILITY, WHETHER IN CONTRACT, TORT OR OTHERWISE,
> ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
> DEALINGS IN THE SOFTWARE.

Source: http://www.boost.org/users/license.html

## Developer
* Developed by *ILT - Institute for Lab Automation and Mechatronics* in Rapperswil (Switzerland). [ilt.hsr.ch](ilt.hsr.ch)
* Commissioned by *Actelion Pharmaceuticals Ltd.* in Allschwil (Switzerland).