HawkCoin
=====================================
> because other low effort altcoins weren't stupid enough.

[![Issues](https://img.shields.io/github/issues/hotcocoaNcode/HawkCoin?style=for-the-badge)](https://img.shields.io/github/issues/hotcocoaNcode/HawkCoin?style=for-the-badge)
<!--- [![Build Status](https://travis-ci.org/litecoin-project/litecoin.svg?branch=master)](https://travis-ci.org/litecoin-project/litecoin)

 Sorry! will add once done refactoring blockchain :P

--->

another stupid litecoin fork

The heck is a litecoins?
----------------

Litecoin is an experimental digital currency that enables instant payments to
anyone, anywhere in the world. Litecoin uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. Litecoin Core is the name of open source
software which enables the use of this currency.

For more information, as well as an immediately useable, binary version of
the Litecoin Core software, see [https://litecoin.org](https://litecoin.org).

So what does that mean about HawkCoin?
--------------------------------------

It's a copy of whatever the Litecoin thing is. Idk i just followed a tutorial i'm not coding god or something, whoever came up with the blockchain idea in the first place is.

WHAT'S A BLOCKCHAIN...?
---

Ok so imagine a thingy that has payments recorded on it, right? You can send and recieve moneys. Anyone can say anyone sent stuff, which requires trust and I have issues with trust so we're going to yeet it for now. Essentially you have a signature like on a piece of paper but code for every transaction on it to make sure it's legit stuff. It also changes the signature each message so that you don't just say "gimme 20 bucks bro" and the last signed one was "1 buck pls" anyway moving on. So now nobody can lie. Poggers pogchampius or something. Now we have to deal with more of my trust issues: WHO THE HECK OWNS THIS DOCUMENT? Like where is this ledger thingy that stores payments? Screw this, everybody gets a ledger. Instead of recodring payments, you record blocks which are tiny ledgers from poeple which contain payments that are signed and verified so you know what's happening and can be sure about it.

Cool so that's the entire thing explained basically

License
-------

HawkCoin Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/litecoin-project/litecoin/tags) are created
regularly to indicate new official, stable release versions of Litecoin Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).

The developer [mailing list](https://groups.google.com/forum/#!forum/litecoin-dev)
should be used to discuss complicated or controversial changes before working
on a patch set.

Developer IRC can be found on Freenode at #litecoin-dev.

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test on short notice. Please be patient and help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write [unit tests](src/test/README.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`. Further details on running
and extending unit tests can be found in [/src/test/README.md](/src/test/README.md).

There are also [regression and integration tests](/test), written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/test) are installed) with: `test/functional/test_runner.py`

The Travis CI system makes sure that every pull request is built for Windows, Linux, and OS X, and that unit/sanity tests are run automatically.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.

Translations
------------

We only accept translation fixes that are submitted through [Bitcoin Core's Transifex page](https://www.transifex.com/projects/p/bitcoin/).
Translations are converted to Litecoin periodically.

Translations are periodically pulled from Transifex and merged into the git repository. See the
[translation process](doc/translation_process.md) for details on how this works.

**Important**: We do not accept translation changes as GitHub pull requests because the next
pull from Transifex would automatically overwrite them again.
