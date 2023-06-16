# vim cheatcodes 

## netrw nav
- `<leader>pv` open tree
- `%` create a new file from tree

## buffer nav
- `h` left
- `j` down
- `k` up
- `l` right

### horizontal nav

- `w` jump word forw
- `b` jump word backw
- `_` jump beginning
- `$` jump end
- `0` jump 0th

- `t + <CHAR>` jump to char right
- `f + <CHAR>` jump prev to char right
- `T + <CHAR>` jump to char ñeft
- `F + <CHAR>` jump prev to char left
    - `;` next iter
    - `,` prev iter
    
### vertical nav

- `{` paragraph up
- `}` paragraph down

- `<C-u>` half page up
- `<C-d>` half page down

- `G` end of file
- `gg` start of file

- `va{` select within curly
- `vi{` select inside curly
- `yap` paste paragraph

## actions

- `d` delete selection
- `u` undo
- `<C-r>` undo²

- `i` insert mode on the spot
- `a` insert mode left

- `I` insert mode line start
- `A` insert mode line end

- `o` insert mode new line down
- `O` insert mode new line up

- `v` visual mode
- `<Sh-v>` visual line

- `y` yank selection
- `p` paste

- `ci"` delete string
- `J` append next line to current

- `<leader>y` yank to clipboard
- `<leader>p` pase from clipboard

## commands 

- `:Ex` open netrw
- `:Sex!`open netrw to the side vertical split
- `:Sex` open filetree to the side horizontal split


- `: + line` jump to line
- `/ + text` search right
    - `n` next
    - `N` prev
- `? + text` -> search left

- `* on word` search word
- `# on word` search word backw

## plugins

### fuzzy finding

- `<leader>pf` fuzzy finder in project
- `<leader>ps` fuzzy finder by word
- `<C-p>` fuzzy finder in git dir

### harpoon

- `<leader>a` add file
- `<C-e>` file 1
- `<C-h>` file 2
- `<C-t>` file 3
- `<C-n>` file 4
- `<C-s>` toggle menu

### undo tree

- `<leader>u` open tree
C-h + H/L -> navigate 
C-w + H/L -> naviate too?
C-w + o -> close

### git

- `<leader>gs` git status
- `=` show changes
- `S` stage chunk
- `S` stage file
- `czz` stage 
- `cc` commit
- `czA` show conflicts
- `dv` show changes splitview
- `gu` select left
- `gh` select right 
- `<leader>p` push

### autocomplete

- `<C-p>` prev
- `<C-n>` next
- `<C-y>` accept
- `<C-<leader>>` display

- `gd` go to def
- `<C-^>` go to prev file
- `<C-o>` go to prev loc


