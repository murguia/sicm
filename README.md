# Working through the Structure and Interpretation of Classical Mechanics

_Structure and Interpretation of Classical Mechanics_ is a book by
Gerald Jay Sussman and Jack Wisdom (https://mitpress.mit.edu/sites/default/files/titles/content/sicm_edition_2/book.html )
that aims to explain classical
mechanics using the variational principle with no ambiguity. It does
this by ensuring that every mathematical expression in the book is in
one-to-one correspondence with an equivalent expression written in
computer code. And computer code is nothing if not precise and
unambiguous.

In this repository, you will find all the code corresponding to the
mathematics in the book, including the numerous interspersed
exercises. This repository also holds the source code for the
underlying Scheme library, `scmutils`, that is heavily employed in the
book, along with notes on how to get all this working on OS X with
`mit-scheme`.


The language of classical mechanics is calculus, along with differential geometry.

Here is a good starter for calculus: [Calculus Made Easy by Silvanus P. Thompson]  (http://calculusmadeeasy.org/)

For differential geometry: [Functional Differential Geometry by Gerald Jay Sussman and Jack Wisdom with Will Farr] (https://mitpress.mit.edu/books/functional-differential-geometry,  download the pdf here:  https://www.dropbox.com/s/t3si4b99ijqyhyk/9580.pdf?dl=1 )


1. High level To whet your appetite: [Physics I: Classical Mechanics by Walter Lewin]
(http://ocw.mit.edu/courses/physics/8-01-physics-i-classical-mechanics-fall-1999/)

2. To get an intuitive feeling for abstract theory: [Classical
Mechanics by Leonard Susskind] (http://theoreticalminimum.com/courses/classical-mechanics/2011/fall)

3. To get a better handle on programming (and Scheme): [Structure and
Interpretation of Computer Programs](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/)

## Installation

1. Install sudo port install mit-scheme (using Macports):

   sudo port install mit-scheme

2. Navigate to `sicm/scmutils/src` and run

   mit-scheme
   (load "compile")
   (load "load")

## License

TODO: GPL v3
