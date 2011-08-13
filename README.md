# Goals
* it contains a set of extensions for three.js
* to avoid repeating the same code over and over... while keeping three.js core small and lean
* the extension should stay small and dont depends from each other if possible
  * aka do a bunch of small plugins, not a monsterous monolitic lib on top of three.js
  * DRY style
  * repository of knowledge, a bit like three.js/examples

# TODO
* folder hierachie not yet known
* should i convert existing lib into this format ?
  * con: it is redundant and will be hard to maintain
  * con: the author of the other lib may not like it as it may be seen as dilluting the effort
  * pro: all libraries would have the same struct...
  * result: dubious avantages, numerous issue and the time to maintain
    * decision: no, use your time on more clearly usefull
  

## possible topic
* some may already exist of not
* window resize is here
* various textures generation
  * from pacexp
* screenshot
* image dragdrop from the desktop to the browser
* various geometry stuff
  * like wobbly
* various material funky
  * like phong + mirrored skybox
* what should go in ther ? what should be independant
* what about strange attactor
  * yep seems nice idea
  * path : new Lorentz(x,y,z, opts)
  * in fact this is a normal path, see about the other implementation
  * where are the other implementation of path, see altereq dev
  * ask mrdoob
