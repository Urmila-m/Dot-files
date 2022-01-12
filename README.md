# Dot-files
This repository contains basic configurations for vim, zsh, bash and tmux. 
It also contains basic aliases for frequently used commands.

In `~/.tmux/.tmux.conf file` (added by oh-my-tmux), comment out 
 ```
 #set -g prefix2 C-a
 #bind C-a send-prefix -2
 ```
 to remove Ctrl-A tmux binding(as an alternative to Ctrl-B) because Ctrl-A is used to navigate to the beginning of the command in bash.
 Then execute the file as `source ~/.tmux/.tmux.conf`.
 
 
