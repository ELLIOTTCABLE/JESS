JESS
====
JESS is your friendly neighbourhood JavaScript pre‐compiler. She allows you to
tie in transformation modules that make your language more friendly.

Usage
=====
She supports two modes of operation: as a source compiler, and as a wrapping
interpreter. These correspond to the two included binaries: `jess` and
`jessc`.

`jessc` operates when passed some JESS sourcefiles, and possibly, a
destination. The sourcefiles will be read, compiled into JavaScript, and
output to the destination.

`jess` is instead used directly… <!-- TODO: Incomplete! -->

Finally, you can acquire `jess.js` (yes, she’s plain JavaScript; I don’t want
to get into a chicken/egg situation where I can’t compile JESS herself into
workable source) and use `jess.process()` directly in your own code. How you
apply this is, obviously, up to you.
