Kampungcoin integration
================================

What is Kampungcoin?
----------------

Kampungcoin is a lite version of Bitcoin using scrypt as a proof-of-work algorithm.

 - 2 minute block targets
 - subsidy halves in 50k blocks
 - ~12 million total coins

The rest is the same as Bitcoin.
 - 10 coins per block

### Automated Testing

Developers are strongly encouraged to write unit tests for new code, and to
submit new unit tests for old code.

Unit tests for the core code are in `src/test/`. To compile and run them:

    cd src; make -f makefile.unix test

Unit tests for the GUI code are in `src/qt/test/`. To compile and run them:

    qmake BITCOIN_QT_TEST=1 -o Makefile.test bitcoin-qt.pro
    make -f Makefile.test
    ./kampungcoin-qt_test

