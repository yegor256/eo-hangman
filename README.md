<img src="https://raw.githubusercontent.com/yegor256/hangman/master/images/logo.png" width="100px"/>

[![Build Status](https://img.shields.io/travis/yegor256/hangman/master.svg)](https://travis-ci.org/yegor256/hangman)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/yegor256/hangman/blob/master/LICENSE.txt)

[Hangman](https://en.wikipedia.org/wiki/Hangman_%28game%29) is a words
guessing game for one player. The computer guesses a word and the user
has to suggest letters one by one. Every time the word contains a letter,
the computer opens it (all of them, if there are a few). Every time the
word doesn't contain a letter, the computer gives a penalty point for
the user. If there are five penalty points, the user looses. If there
are no hidden letters anymore, the computer looses.

The game is implemented in [EOLANG](https://www.eolang.org). The source
code is in `/eo` directory. The code may compile to different target
VMs, including Java, Ruby, etc. Each build system is in its own directory,
such as `/jvm`, `/ruby`, etc.

To build them all, run:

```
$ make
```

In order to run on a specific target VM, go one of the subdirectories
and read `README` there.

If any ideas, submit a pull request.