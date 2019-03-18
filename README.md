# Tmux_operation
Record some frequently-used command

## create a window
tmux <br/>
tmux new  <br/>
tmux new -s [name] <br/>

## detach from a window
tmux detach <br/>
crtl + b, then d <br/>

## attach a window
tmux attach <br/>
tmux attach-session -t (num) <br/>

## show all the window
tmux ls 

## kill a window
tmux kill-session (-t (num)) 
