# VIM + Tmux [Video](https://www.youtube.com/watch?v=5r6yzFEXajQ&t=21s)

## Features
### Modal Editing
1. Normal mode -> navigate, delete, change lines
2. Insert mode -> edite
3. Visual mode -> Highlight portions to manipulate
4. Ex mode -> command mode

#### Normal mode
* to navigate: H J K L.
..* Why H J K L? -> because the first keyboards where vim & vi was developed used this keys as arrow keys
* usefull commands:
..* ^e / ^y -> scroll up & down
..* ^f / ^b -> scroll up/down a full page
..* H -> cursor to the top of the window
..* M -> cursor to the middle of the window
..* L -> cursor to the bottom of the window
..* gg/GG -> Top / Bottom of the file

* text objects & motions
..* w -> Move to the next word's beginnging
..* e -> Move to the next word's ending
..* {number}d+i+w -> delete the word where cursor is
..* {number}c+a+w -> change the word where cursor is
..* c+w -> change word starting with the cursor
..* d+w -> same but keeps spaces
..* y+i+<char> -> yank text inside <char>
..* d+i+<char> -> delete inside the <char>
..* v+a+<char> -> visually select all content inside <char>
..* v+i+<char> -> visually select content inside <char>
..* Use . to repeat the last executed command: c+i+" --> edit + ESC --> go to other line --> . = Magic :)
..* dd/yy -> delete / copy entire line

