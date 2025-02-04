Original README file
===============================================================================
TinyWM is written by Nick Welch <nick@incise.org> in 2005 & 2011.

This software is in the public domain and is provided AS IS, with NO WARRANTY.

TinyWM is a ridiculously tiny window manager implemented in nearly as few lines
of C as possible, without being obfuscated or entirely useless. It allows you
to move, resize, focus (sloppy), and raise windows -- that's it!  TinyWM's main
purpose is to serve as a quick example of some window manager programming
basics.

Files:

  Makefile: highly advanced build system
  tinywm.c: the code
  annotated.c: same, but with tons of rambling comments about everything
  tinywm.py: a python version (requires CVS python-xlib due to a bug)

Usage:

  Focus follows pointer.
  Alt+Button1, drag: interactive window move
  Alt+Button3, drag: interactive window resize
  Alt+F1: raise focused window

Misc:
  
  Another very small window manager is failsafewm.  Originally I started
  hacking on it, as there was quite a bit of stuff in it that I thought was
  unneeded.  I wound up rewriting it from scratch, with just the bare
  necessities, and that became TinyWM.

    http://freshmeat.net/projects/failsafewm/

  Yet another small -- but in comparison to TinyWM, big -- window manager is
  aewm.  It's a good example for learning about writing a window manager.

      http://www.red-bean.com/~decklin/aewm/

