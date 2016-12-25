Old Hungarian (Hungarian Runic) keyboard layout
===============================================

In order to make Old Hungarian (Hungarian Runic) Unicode characters easy
to type, I've created this keyboard layout. It should be used in conjunction
with an Old Hungarian display font, such as
[this one](https://github.com/OldHungarian/old-hungarian-font).

Design decisions
----------------

In this current version, I use only the "small" characters from the Unicode
set, and don't use the "capitals". The only difference between the two is
their size, and I felt it was better to include all the characters than to have
two sizes of only a majority of characters with several missing.

Also, note the the following characters are not represented on the keyboard,
as they are not present in the Old Hungarian Unicode block: DZ, DZS, Q, W, X, Y.
In some fonts, as in the one linked above, they are represented as ligatures.
The zero-width joiner character (U+200D) has been added to both the left and
right sides of the keyboard for ease in creating these ligatures.

Since not all digits are represented in Old Hungarian (for example, 2 is
represented as 11), the unused digit keys are used for punctuation and other
symbols.


Unshifted keyboard layout
-------------------------
![Display of keyboard layout with no Shift keys applied](images/rovas.png)

Keyboard layout with Shift key
------------------------------
![Display of keyboard layout with Shift key applied](images/rovas-shift.png)

Keyboard layout with AltGr key (or Ctrl-Alt)
--------------------------------------------
![Display of keyboard layout with AltGr (or Ctrl+Alt) key applied](images/rovas-altgr.png)

Keyboard layout with AltGr and Shift keys
-----------------------------------------
![Display of keyboard layout with AltGr and Shift keys applied](images/rovas-altgr-shift.png)
