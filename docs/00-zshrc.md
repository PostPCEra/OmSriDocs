
# source : https://news.ycombinator.com/item?id=22125306
#
alias manu="cheat"        # Usage examples of a command ( with man page like options)
alias mano="manflags"     # Options of a command as specified in man page
alias mane="explain"     # Explain the command what it does based on man page entree

# Once you edit this file do,  $source ~/.zshrc so changes are activated in the current shell window

#############################################################################
# SR: All the below pased from this URL https://news.ycombinator.com/item?id=22125306
# this is basically using a) cheat b)manpages c) maniker d) TLDR; etc..
#############################################################################

# 
cheat() { 
   curl "http://cheat.sh/$1"
  }
  
  cht() { 
   curl "http://cheat.sh/$1"
  }

  man2txt() {
    man "$1" | col -bx
  }

  manflags(){
    man "$1" | awk '{$1=$1;print}' | grep "^\-" | more
  } #man pages just the flags more or less, captures some extra 

  ubuman() { 
   w3m -dump "https://manpages.ubuntu.com/manpages/bionic/en/man1/"$1".1.html"
  } # ubuntu web manpages note bionic, update with do release up

  ubumanflags() { 
   w3m -dump "https://manpages.ubuntu.com/manpages/bionic/en/man1/$1.1.html" | \
   awk '{$1=$1;print}' | grep "^\-"
  } # ubuntu web manpages

  explain () {
    if [ "$#" -eq 0 ]; then
      while read  -p "Command: " cmd; do
        curl -Gs "https://www.mankier.com/api/v2/explain/?cols="$(tput cols) --data-urlencode "q=$cmd"
      done
      echo "Bye!"
    elif [ "$#" -eq 1 ]; then
      curl -Gs "https://www.mankier.com/api/v2/explain/?cols="$(tput cols) --data-urlencode "q=$1"
    else
      echo "Usage"
      echo "explain                  interactive mode."
      echo "explain 'cmd -o | ...'   one quoted command to explain it."
    fi
  }
# notetoself: check ```info``` check ```help``` check ```apropos``` check ```whatis```
