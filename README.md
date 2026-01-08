# terminal wrapped!

[screenshot would go here]

Reads in your shell's history file (for now just`~/.bash_history` or `~/.zsh_history`)
and makes a little command line "wrapped" in the terminal with various stats over
your commands (if there are no timestamps then it just uses all the data)

So far the stats are:
  "Top commands"
  "Top cd targets" + "Top z targets" (since lots of people use zoxide or something) 
  "Day of week" (Only if `export INC_APPEND_HISTORY=true` in zsh) 
  more... 
  
You can install it is `pip install terminal-wrapped` (or `uvx run terminal-wrapped` or `pipx terminal-wrapped`)
and then just run `terminal-wrapped` in you shell. 
