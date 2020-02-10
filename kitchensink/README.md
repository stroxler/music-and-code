# kitchensink

This stack project is a "kitchen sink" where I demonstrate
that all of the Haskell music libraries I've been looking
at recently can be installed side-by-side:
 - vivid for raw supercollider interaction, especially synths
 - Euterpea for algorithmic composition
 - Tidal for supercollider livecoding

I'm not yet sure whether I'll actually wind up using these
libraries together; for now I'm just verifying that the stack
build works and dropping some learning examples into
`tidal-scripts`.

To get an atom session hooked up to this stack env, run
```
stack exec atom .
```
from this directory root.
