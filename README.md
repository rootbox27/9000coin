9000coin integration/staging tree
================================

http://www.9000coin.org

Copyright (c) 2009-2014 Bitcoin Developers
Copyright (c) 2011-2014 Litecoin Developers
Copyright (c) 2016	9000Coin Developer

What is 9000coin?
----------------

9000coin is a fork of Litecoin using scrypt as a proof-of-work algorithm.
 - 2.5 minute block targets
 - subsidy halves in 450k+ blocks (~2 years)
 - over 9000 total coins
 - 0.01 coins per block
 - fast retarget difficulty

For more information, as well as an immediately useable, binary version of
the 9000coin client sofware, see http://www.9000coin.org.

License
-------

9000coin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Testing
-------
Unit tests for the core code are in `src/test/`. To compile and run them:

    cd src; make -f makefile.unix test

Unit tests for the GUI code are in `src/qt/test/`. To compile and run them:

    qmake BITCOIN_QT_TEST=1 -o Makefile.test 9000coin-qt.pro
    make -f Makefile.test
    ./9000coin-qt_test

