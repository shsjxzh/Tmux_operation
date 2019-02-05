# Tmux_operation
Record some frequently-used command

## create a window
tmux 
tmux new  

## detach from a window
tmux detach 
crtl + b, then d 

## attach a window
tmux attach 
tmux attach-session -t (num) 

## show all the window
tmux ls 

## kill a window
tmux kill-session (-t (num)) 
