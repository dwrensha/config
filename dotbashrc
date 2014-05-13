# write to .bash_history after every new command
export PROMPT_COMMAND="history -a"

# color the prompt based on the previous status code
export PS1='\[\e[0;$(if [ $? = 0 ]; then echo 32m; else echo 31m; fi)\]\u@\h\[\e[0m\]:\[\033[01;34m\]\w\[\033[00m\]\$ '
