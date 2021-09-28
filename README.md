
Imagine SD-WAN - universal network link bonding and multichannel VPN.



SD-WAN a Linux VPN daemon used to combine several connection paths 
into one aggregated channel. Features latency, reordering and jitter 
management, behaviour analysis optimizations for encapsulated protocols, 
bufferbloat control, packet redundancy, and multiple cpu cores utilization. 
Up to 30 heterogenous links bonding supported. Used for live streaming, 
LTE/3G/Wi-Fi link bonding. 32/64-bit, x86, MIPS and ARM supported. 
Supports python plug-ins for new algorithms implementation. 


## Compilation and Installation:

In order to compile vtrunkd you need several software packages.
Required packages: 
  - Good C compiler (gcc, egcs, etc)
  - GNU Make (make)
  - GNU libtool (libtool)
  - Lexical Analyzer (flex, lex)
  - YACC (yacc, bison, byacc)
  - Universal TUN/TAP driver 	http://vtun.sourceforge.net/tun
  
On ubuntu, run: 

    $ sudo apt-get install build-essential flex bison
    $ ./configure --prefix=
    $ make
    $ sudo make install
----

vtrunkd and vtrunkd algorithm (C) Andrew Gryaznov

Based on Vtun (C) 1998-2004 Maxim Krasnyansky

This product includes software developed by the OpenSSL Project
for use in the OpenSSL Toolkit. (http://www.openssl.org/).

