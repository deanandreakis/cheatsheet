# NeoVim

1. leader: " "
2. NeoVim Tree: \<C-o\>
3. Telescope Find Files: \<C-p\>
4. Telescope Live Grep: \<C-r\>

## Move highlited sections in Visual Mode (respecting indents)
1. Move Up: J
2. Move Down: K

## Moves then appends line below cursor to the current line & leaves cursor at beginning of line in Normal Mode
J

## Half page vertical jumps but leaves cursor in the middle in Normal Mode
1. \<C-d\>
2. \<C-u\>

## Allows search terms to stay in the middle of the page in Normal Mode (cursor stays in the middle)
1. n
2. N

## When pasting/replacing a highlited selection, this will keep the original yanked text in the paste buffer
\<leader\>p

## Copy into system copy buffer
1. Normal and Visual Mode: \<leader\>y
2. Normal Mode: \<leader\>Y

## Delete into the void register in Normal and Visual Mode
\<leader\>d

## Format the current buffer in Normal Mode
\<leader\>f

## Opens a global search and replace on item under the cursor in Normal Mode
\<leader\>s

## LSP (Normal Mode Unless Otherwise Indicated)
1. Definition: gd
2. Hover: K
3. Workspace Symbol: \<leader\>vws
4. Diagnostic Open Float: \<leader\>vd
5. Diagnostic Goto Next: [d
6. Diagnostic Goto Previous: ]d
7. Code Action: \<leader\>vca
8. References: \<leader\>vrr
9. Rename: \<leader\>vrn
10. Signature Help (Insert Mode): \<C-h\>

## Mason LSP Manager
:Mason
:LspInfo

## Packer Plugin Sync
:PackerSync

## Completion (i.e. if the completion floating window is active)
1. Select Previous: \<C-p\>
2. Select Next \<C-n\>
3. Confirm: \<C-y\>
4. Complete: \<C-Space\>

## Commenting Code
1. Comment/Uncomment Code in Visual Mode: gc
2. Comment/Uncomment A Single Line in Normal Mode: gcc

## NeoVim Tree
See/Close All Key Mappings: g?


