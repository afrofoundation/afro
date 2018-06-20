The Berkeley DB library version used for the released
official Windows binary wallet is 6.1.26.

Please keep this in mind if you elect to compile from
the sources and plan on porting the wallet.dat files across
your different installations.

We recommend that you do not port the wallet.dat files across
installations unless you know what you are doing.

Using the "dumpwallet" and "importwallet" console commands
is the recommended way of moving a wallet between installations.
To move a specific address, you can use the "dumpprivkey" and
the "importprivkey" commands.





AFRO coin specification

Coin Name: AFRO

Ticker: AFRO

Coin Type: POS / MN

Maximum block size: 3 MB

Block time: 72 sec

MINIMUM STAKE AGE: 24 hours

Coinbase maturity: 45

Minimum TX fee: 0.01 AFRO

P2P port: 22516

RPC port: 22517

To build the daemon:
- cd src
- make -f makefile.unix

To build the GUI wallet:

- change directory to the repository top level
- type qmake
- type make

