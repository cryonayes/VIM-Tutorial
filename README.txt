There is 2 different modes on vim
1) View mode
2) Insert mode

ESC    -> change into view mode
:      -> command input
hjkl   -> moving on page, h left, j down, k up, l right
gg     -> go to the beginning of the file
G      -> go to the end of the file

H      -> go to top of screen 
M      -> go to middle of screen
L      -> go to bottom of screen

{      -> skip block up
}      -> skip block down
$      -> go to the end of the line
^      -> go to the first word of the line
0      -> go to the beginning of the line
:(num) -> jump to specific line
w      -> skip word
W      -> skip word (ignore punctuation)
b      -> skip word backward
B      -> skip word (ignore punctuation)
t(chr) -> go to specific character on line (before char, search after cursor)
f(chr) -> go to specific character on line (on char, search after cursor)
T(chr) -> go to specific character on line (before char, search before cursor)
F(chr) -> go to specific character on line (on char, search after cursor)
%      -> go to other pair of paranthesis 
zz     -> center page
/      -> search
n      -> next found instance
N      -> previous found instance
*      -> other instances of word that cursor points
;      -> next instance when using t,f
,      -> previous instance when using t,f 
.      -> repeat last command


c(cmd) -> change characters
~      -> change the case of a letter
r      -> replace letter
R      -> replace mode

i      -> insert mode (before)
I      -> insert mode (beginning of line)
a      -> insert mode (after)
A      -> insert mode (end of line)
o      -> insert new line below
O      -> insert new line above

u      -> undo
ctrl r -> redo


dd     -> delete line (also yanks line)
x      -> delete character
D      -> delete after cursor
yy     -> copy line
p      -> paste line below
P      -> paste line above

V      -> visual mode to select lines
v      -> visual mode to select words

q(chr) -> macro mode, end with q
@(chr) -> replay saved macro
@@     -> rerun last macro

below  -> creates new window and places below of the active window
top    -> creates new window and places top of the active window
ctrl w - -> shrinks the selected window
ctrl w + -> expands the selected window

tabnew -> creates new tab
tabnext-> switches to the next tab
tabprevious -> switches to the previous tab

Examples:

d3w    -> delete 3 words
y3w    -> yank 3 words
dt"    -> delete to "
3j     -> 3 lines down
di"    -> delete inside "
dG     -> delete to the bottom of the file

d{     -> delete above block
d}     -> delete below block

