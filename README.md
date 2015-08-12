![Tags: Five in a Row, Tic Tac Toe, TicTacToe, 5 in a Row, Go-Moku, Connect, Connect5, Connect6, Caro, Noughts and Crosses, Gomoku, Renju, Pente, Piskvork, Amoba, Kółko i Krzyżyk, Gomocup, AI, Engine, Artificial Intelligence, Brain, Pbrain, Gra, Game, Source Code Files, Program, Programming, Github, Board, Coding.](GomokuSS.png "Tags: Five in a Row, Tic Tac Toe, TicTacToe, 5 in a Row, Go-Moku, Connect, Connect5, Connect6, Caro, Noughts and Crosses, Gomoku, Renju, Pente, Piskvork, Amoba, Kółko i Krzyżyk, Gomocup, AI, Engine, Artificial Intelligence, Brain, Pbrain, Gra, Game, Source Code Files, Program, Programming, Github, Board, Coding.")

Welcome to Gomoku.app !

WHAT IS IT
==========

Gomoku.app is an extended TicTacToe game for GNUstep.  You win the
game if you are able to put 5 of your pieces in a row, column or
diagonal.  You lose if the computer does it before you.

Most of the development effort was concentrated on the artificial
intelligence engine used by the computer while playing.  Unlike most
other engines, this engine is not designed to play very well, but
rather to give you fun when you play against it.

COPYING
=======

This program is free sofware, released under GNU GPL 2.0.

COMPILING
=========

Please check the 'INSTALL' file to build the game on GNUstep, and the
'INSTALL.OSX' file to build the game on Apple/Mac OS X.

RUNNING THE PROGRAM IN ANOTHER LANGUAGE
=======================================

The program has been translated into the following languages: 

 English
 Italian (by Nicola Pero <nicola.pero@meta-innovation.com>)
 French (by Emmanuel Maillard <e.rsz@libertysurf.fr>)
 Swedish (by Erik Dalen <dalen@jpl.nu>)
 Spanish (by Rodrigo Sancho Senosiain <ruysan@wanadoo.es>)
 German (by Matthias Zoellner <matthias.zoellner@fen-net.de>)
 Traditional Chinese (by Yen-Ju Chen <yjchenx@hotmail.com>)
 Hungarian (by Varga Peter <debbug123@freemail.hu>)
 Norwegian (by Per Christian Gaustad <svele@netcom.no>)

Under GNUstep, to run Gomoku.app in your preferite language, for
example Italian, set your GNUstep preferences to use that language by
giving the following command at the shell prompt:

defaults write NSGlobalDomain NSLanguages "(Italian)"

To translate it into another language, just take the
English.lproj/Localizable.strings, translate each string into your
language (look at Italian.lproj/Localizable.strings for an example),
put everything into a new YourLanguage.lproj/Localizable.strings.  Add
your language to the GNUmakefile.  Ah - and don't forget to send the
result of your work to nicola.pero@meta-innovation.com so it can be
included in the next release !

BOARDS OF DIFFERENT SIZES
=========================

If you get bored with the standard board, you can play the game on
boards of different size; the default size is 8 but 10 is also nice to
play.  Pass the size of the board as argument of Gomoku.app.  For
example, to play on a 10x10 board, you can start Gomoku with:

openapp ./Gomoku.app 10 

Warning: board size must be >= 8.

BUGS
====

Please mail them to <nicola.pero@meta-innovation.com>

HOMEPAGE
========

http://www.gnustep.it/nicola/Applications/Gomoku/

THANKS
======

To David Relson <relson@osagesoftware.com>, for providing support for
boards of arbitrary sizes.

Tags: Five in a Row, Tic Tac Toe, TicTacToe, 5 in a Row, Go-Moku, Connect, Connect5, Connect6, Caro, Noughts and Crosses, Gomoku, Renju, Pente, Piskvork, Amoba, Kółko i Krzyżyk, Gomocup, AI, Engine, Artificial Intelligence, Brain, Pbrain, Gra, Game, Source Code Files, Program, Programming, Github, Board, Coding.
