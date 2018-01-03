Newcoin Core Fork of Bitcoin v0.10.1
=====================================



What is Newcoin?
----------------

Newcoin is an experimental new digital currency that enables instant payments to
anyone, anywhere in the world. Newcoin uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. Newcoin Core is the name of open source
software which enables the use of this currency.


How to Compile
-------------------
Run these commands from project root directory

autoreconf --install
aclocal
automake --add-missing
./configure --with-incompatible-bdb
make



