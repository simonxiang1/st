## personal build of st terminal
todo list:
- transparency (if I need it, patch in alpha, selection colors, selectionbg-alpha, then get picom working) 
  - note that alpha conflicts with pywal somehow, read the man page for pywal
- make it nicer w/zsh (weird arrows and banners)
- change the font (if I want to... do I?)

done:

- custom keybindings! 
  - Ctrl-j and Ctrl-k to scroll down and up respectively
  - Ctrl-d and Ctrl-u for fast scrolling!
  - Ctrl-J and Ctrl-K for zooming on the spot, Ctrl-P to reset
  - Ctrl-c and Ctrl-v to copy and paste (windows binds)
- patched in anysize and font2 for fallback font
- patched in xresources support and scrollback
- got pywal to work! it's amazing and updates on the fly
- patched in blinking cursor (good old windows feel)
- fixed japanese characters!!! (locale problem)
