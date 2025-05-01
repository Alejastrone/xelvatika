Xelvatika Core integration/staging tree
=====================================

What is Xelvatika?
----------------

Xelvatika is an experimental digital currency that enables instant payments to
anyone, anywhere in the world. Xelvatika uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. Xelvatika Core is the name of open source
software which enables the use of this currency.

For more information, as well as an immediately usable, binary version of
the Xelvatika Core software, see, or read the original whitepaper.

License
-------

Xelvatika Core is released under the terms of the MIT license. See COPYING for more
information.

Development Process
-------------------

The `master` branch is regularly built (see `doc/build-*.md` for instructions) and tested, but it is not guaranteed to be
completely stable. are created
regularly from release branches to indicate new official, stable release versions of Xelvatika Core.

The repository is used exclusively for the
development of the GUI. Its master branch is identical in all monotree
repositories. Release branches and tags do not exist, so please do not fork
that repository unless it is for development reasons.

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test on short notice. Please be patient and help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write for new code, and to
submit new unit tests for old code. 
The Travis CI system makes sure that every pull request is built for Windows, Linux, and macOS, and that unit/sanity tests are run automatically.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.

Translations
------------

Changes to translations as well as new translations
