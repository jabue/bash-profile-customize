# bash-profile-customize

"#!/bin/bash"
#THIS MUST BE AT THE END OF THE FILE FOR SDKMAN TO WORK

#personal options
alias ll='ls -la'
alias c='clear'
alias h='history'

print_before_the_prompt () {
    echo "--------------------------------------------------------------"
}
 
PROMPT_COMMAND=print_before_the_prompt
PS1='\n\u:[\w]->'
    


#---------------tool home directory setup-----------------#
#grails env
GRAILS_HOME="~/Documents/grails/grails-3.0.8/"
PATH=".:$PATH:$GRAILS_HOME/bin"
export GRAILS_HOM
