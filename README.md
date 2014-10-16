### Universal find-in-file notation
I use this simple notation system in conjunction with a texteditor's find-in-file search function. The defined glyphs are used within comments, preferably at the start of new lines, and in most cases are followed by a concise accompanying note.

##### Glyphs v3.0:
```
  @@@ : NB      : Generic find-in-file prefix (for HTML, use <!--@@@ -->)
  >>> : MEAT    : Add some meat to this dummy/skeleton codeblock
  <<< : GUT     : Remove this unused/unecessarily large codeblock
  ^^^ : REFACTOR: Neaten up, improve or rework the internals of this system
  VVV : HUNT    : Hunt out and remove all references/dependencies to this codeblock
  <-> : SPLIT   : Pull this codeblock apart, into more manageable/reusable chunks
  >-< : UNIFY   : Merge this codeblock with another near-identical block 
  +++ : BUILD   : Accompanying comment suggests a new feature
  ??? : PONDER  : Reconsider the implementation/necessity of this codeblock
  !!! : KILL    : Fix this inconsistency / bug
```
