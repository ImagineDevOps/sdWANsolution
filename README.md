
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

On ubuntu, run: 

    $ sudo apt-get install build-essential flex bison
    $ ./configure --prefix=
    $ make
    $ sudo make install
----




