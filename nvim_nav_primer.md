# Nvim navigation primer


## Core Movement (Normal Mode)
### HJKL Basics
`h` ← | `j` ↓ | `k` ↑ | `l` →  
**Mnemonic:** Left-to-right home row arrows (j descends below line)

### Advanced Motions
`w` (next Word) | `b` (Back) | `e` (End)  
`0` (line start) | `$` (line end) | `gg`/`G` (file start/end)  
**Mnemonic:** "w, b, e" = alphabetical word motions

## Window Management
### Splitting
`:sp` (horizontal Split) | `:vsp` (Vertical split)  
**Mnemonic:** "sp" = split pane, add "v" for vertical

### Navigation
`<C-w>h/j/k/l` (window HJKL) | `<C-w>w` (Window cycle)  
`<C-w>+/-` (height) | `<C-w></>` (width)  
**Mnemonic:** `<C-w>` = "window control" prefix

## Buffer Navigation
`:bn` (Buffer Next) | `:bp` (Buffer Previous)  
`:bd` (Buffer Delete) | `:b#` (alternate Buffer)  
`:ls` (List buffers) | `:b N` (buffer by Number)  
**Mnemonic:** All start with "b" for buffer

## Tab Navigation
`:tabnew` | `gt` (Go Tab) | `gT` (Go Tab back) | `Ngt` (tab N)  
**Mnemonic:** "gt" sounds like "go tab"

## Navigation History
`<C-o>` (Older) | `<C-i>` (Inverse/newer)  
**Mnemonic:** Adjacent keys on keyboard

## Pro Tips
1. Prefix patterns: No prefix = text, `<C-w>` = window, `:b` = buffer
2. Visual mnemonics: `$` = line end (like regex), `>` grows right
3. Most commands follow verb-noun pattern (e.g., "buffer delete")
