
% create a new file from tree

leader pv -> open netrw

h j k l -> basic motions

w -> word forward
b -> word backward

d -> delete command
u -> undo command
C-r -> undo undo command

i -> insert mode 
a -> move left and insert mode
I -> go to beginning of line in insert mode
A -> go to end of the line in insert mode
o -> new line below in insert mode
O -> new line above in insert mode

v -> visual mode
y -> yank (copy selection)
p -> paste selection

S-v -> visual line mode

_ -> beginning
$ -> end
0 -> 0th character

f + char -> jumps to char
t + char -> jumps up to char 
    -> ; next
    -> , previous

F or T -> jumps backwards

:Ex -> open filetree
:Sex! -> open filetree to the side vertical split
:Sex -> open filetree to the side horizontal split

{ -> up by paragraph
} -> down by paragraph

C-u -> jump half page up
C-d -> jump half page down

G -> all the way down
gg -> all the way up

: + line -> to that line
/ + text -> search -> n/N to go next/prev
? + text -> backwards search

* on word -> search that word
# on word -> search that word backwards

va + { -> selects everything within curly braces
vi -> same but inside
yap -> pase paragraph
PLUGINS

leader pf -> find files in project overall
leader ps -> find by word
C-p -> find files in git

leader a -> add to harpoon
C-e -> toggle quick menu
C-h -> nav 1
C-t -> nav 2
C-n -> nav 3
C-s -> nav 4

leader u -> undo tree
C-h + H/L -> navigate 
C-w + H/L -> naviate too?
C-w + o -> close

leader gs -> git status
within gs -> = show changes / = undo
select a chunk and S -> commits chunk
S on file -> stage file

czz -> stage changes
cc -> commit 
czA -> conflict
C-w o -> jump up
dv on main -> see changes in both sides
C-w = -> equal length of the windows

gu -> select left
gh -> select right
leader p -> push



C-p/C-n -> autocompletion prev/next
C-y -> accept autocompletion
C-space -> start completion

gd -> jump to definition
C-^ -> go to previous file
C-o -> go back to previous file location

ci" -> delete string

:%s -> do to the whole files

J/K on V mode -> move selection
J append next line into current one

leader p -> copy and keep register
leader y -> copy into clipboard register

