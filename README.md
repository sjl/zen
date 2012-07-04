# Zen

A simple, roguelike not-quite game.  Basically I wanted to play around with
getting a roguelike up and running end-to-end in Clojure.

[Screencast Demo](http://www.screenr.com/QKZ8)

![Screenshot](http://i.imgur.com/JQu55.png)

It's about 256 lines of code with comments for the meat of the game, and another
80-ish that wrap Lanterna to make it more Clojurey.  It's certainly not the
best/prettiest code.  Consider it a throwaway experiment.

## Usage

Requires Leiningen 2.

    lein deps
    lein trampoline run
    lein trampoline run

Yeah, you need to run `lein trampoline run` twice -- I have no idea why.

## License

Copyright 2012 Steve Losh

MIT/X11 Licensed.
