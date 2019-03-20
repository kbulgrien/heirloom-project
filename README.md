##The Heirloom Project

This is a mirror of [The Heirloom Project](http://heirloom.sourceforge.net)
CVS repositories — a collection of hisorical UNIX tools, principally derived
from System V, which have been patched to build on a modern system.

Particularly noteworthy are its historical Bourne shell, toolchain, and source
code management tools — it includes some of the original implementations of
m4, lex, yacc, SCCS, troff, etc.

Also included here are the related original [vi](http://ex-vi.sourceforge.net)  and [nail](http://heirloom.sourceforge.net/mailx.html) (mailx) repositories.

Changes relative to "https://github.com/eunuchs/heirloom-project":

* Reformat and add of fork change notes in this file.
* Added original heirloom-project files found to be missing as determined by a
  check out the original repository at "http://heirloom.cvs.sourceforge.net/".
  The files are apparently missing due to presence of files that cannot reside
  simultaneously on a case-insensitive file system:

  Added:

    heirloom/heirloom-doctools/troff/troff.d/font/devpost/HB
    heirloom/heirloom-doctools/troff/troff.d/font/devpost/HB.name
    heirloom/heirloom-doctools/troff/troff.d/font/devpost/HI
    heirloom/heirloom-doctools/troff/troff.d/font/devpost/HI.name
    heirloom/heirloom-doctools/troff/troff.d/font/devpost/HX
    heirloom/heirloom-doctools/troff/troff.d/font/devpost/HX.name
    heirloom/heirloom-doctools/troff/troff.d/font/devpost/charlib/LH

  Pre-existing:

    heirloom/heirloom-doctools/troff/troff.d/font/devpost/Hb
    heirloom/heirloom-doctools/troff/troff.d/font/devpost/Hb.name
    heirloom/heirloom-doctools/troff/troff.d/font/devpost/Hi
    heirloom/heirloom-doctools/troff/troff.d/font/devpost/Hi.name
    heirloom/heirloom-doctools/troff/troff.d/font/devpost/Hx
    heirloom/heirloom-doctools/troff/troff.d/font/devpost/Hx.name
    heirloom/heirloom-doctools/troff/troff.d/font/devpost/charlib/lh

