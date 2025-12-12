### Installation
1. Put `uikeys.txt` in `~/.local/state/Beyond All Reason/` and `Hotkeys/` in `~/.local/state/Beyond All Reason/LuaUI/`
2. For cheatsheet, create `~/.local/state/Beyond All Reason/luaui/images/keybinds` and put desired `grid_keys.png` *(or other: https://github.com/beyond-all-reason/Beyond-All-Reason/tree/master/luaui/images/keybinds)* picture there.
### Keymap visualisation
<img width="959" height="779" alt="2025-12-12_14-22" src="https://github.com/user-attachments/assets/742aa4d5-6a0c-4935-9f1e-559c040bf8f7" />

Coloured words on the keys correspond to the Alt (yellow), Ctrl (green), Shift (purple) modifiers. Keys that are combinations of multiple modifiers are ommited.
### Keybinds with multiple modifiers
```txt
bind Alt+Ctrl+sc_q remove_from_autogroup

bind Ctrl+Alt+sc_d selfd queued

bind Ctrl+Alt+1 pause
bind Ctrl+Alt+2 LastMsgPos
bind Ctrl+Alt+3 ShowPathTraversability
bind Ctrl+Alt+4 ShowMetalMap
bind Ctrl+Alt+5 ShowElevation

bind Shift+Alt+sc_x buildspacing inc
bind Shift+Alt+sc_z buildspacing dec

bind Ctrl+Shift+sc_d blueprint_delete

bind Any+Shift+sc_g commandinsert prepend_between
bind Any+Shift+sc_b commandinsert prepend_queue
```
### Meta (enter) key usage
```
bind meta+tab select Visible+_Builder_Idle_Not_ManualFireUnit_Not_Building_Not_Resurrect+_ClearSelection_SelectAll+

bind meta+1 group selectadd 1
bind meta+2 group selectadd 2
bind meta+3 group selectadd 3
bind meta+4 group selectadd 4
bind meta+5 group selectadd 5
bind meta+Shift+1 group selectadd 6
bind meta+Shift+2 group selectadd 7
bind meta+Shift+3 group selectadd 8
bind meta+Shift+4 group selectadd 9
bind meta+Shift+5 group selectadd 0
```
