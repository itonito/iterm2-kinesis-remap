# iterm2 remap configuration for Kinesis keyboard

There must be 65535 mac users with a kinesis keyboard who accidentally closed the terminal with command-w key when trying to delete a word.

So, here is a remap file for those who wants to use iterm2 like terminals on Ubuntu Linux. 

## Installation

Go to Preference > Keys > Key Bindings > Presets and load iterm2-keymap.itermkeymap from "Import" tool.

## Other handy tips to make iterm2 behave better

1. Using Alt(option) key to traverse back and forth on cli

   Preference > Profiles > Keys

   Set "Esc+" for Left Option key

2. Disable activating vim "Visual Mode" on mouse drag

   Preference > Profiles > Terminal

   Uncheck "Report mouse clicks & drags"

3. Copy selection on mouse drag

   Preference > General > Selection

   Enable "Copy to pasteboard on selection"

4. Paste on right click, and remap context menu to "command right mouse button"

   Preference > Pointer > Bindings

   "Command + Right button single click" > "Open Context Menu"

   "Right button single click" > "Paste from Clipboard: ConvertPunctuation"  
