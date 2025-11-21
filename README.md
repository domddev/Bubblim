# Bubblim - CosmosOS Text Editor

Bubblim is forked from MIV, a text editor for CosmosOS. Bubblim is already a built-in Text Editor in BubbleOS.

 - Bubblim functions and name are similar to VIM.

It is possible to pass argument:
 - bubblim(null) - open blank page
 - bubblim(String) - open page with String
 
Possible action inside editor:
 - i (Enter INSERT mode)
 - ESC button (Exit INSERT mode)
 - :wq (Save and Exit), returns String of text
 - :q (Quit without saving), returns null
