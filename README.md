## Welcome Readers

Thanks for taking the time to read my project I am building for fun.

## script for details
```bash
## TABLE MENU
 @1 [DATA]
  print "preservation of DATA"
 
 DATA: relay patch msg: networker

 @2 [META]
  print "preservation of META TAGS" "<pre>" "<code>" "import link command" 
 
 case: while true command

  'system::model'
  'system::patch'
  'system::connect'
  'system::network'
  'system::relay'
  'system::configuration'
  'system::settings'

 @3 [BUILD]
  + application build
  + other details included
  + etc.
 @4 [UPDATE]
  + Any and all fixes related to the project

    A.) test make a file
    B.) test via command line tools
    
## Project Details
To design an application that can serve as a foundation.
Each test case is a test for patching issues.

command[ ./b./t./c./command. ]

+ A.) test case
+ B.) retry what doesnt work
+ C.) doing it right the first time around -- slow down coding
  
## Project Specs For Installation

npm project build
npm install build project
npm install command toolset

@BEGIN SYS.caller-project
import system;
return 0;
return 1;
-- KEY BLOCK --
import system from os1;
use strict;
use warnings;
qw('readonly DATA')
-- INNER MESSAGE --
<!doctype html>
<pre>
<code>
abcdefghijklmnopqrstuvwxyz
acegikmoqsuwyzxvtrpnljhfdb
qazwsxedcrfvtgbyhnujmikolp
qwertyuiopasdfghjklzxcvbnm
</code>
</pre>
-- END INNER MESSAGE --
-- BLOCK END --
## Networker
// add additional DATA here.
?
from tkinter import *
from easygui import fileopenbox

root = Tk()
root.title("Word Counter")
root.geometry("500x500")

app = Frame(root)
app.grid()
button1 = Button(app, text = "Browse for a file")
button1.grid()

button2 = Button(app)
button2.grid()
button2.configure(text ="Count the file")

button3 = Button(app)
button3.grid()
button3["text"] = "Exit"

root.mainloop()

def word_count(filename):
    filename = fileopenbox()
    if not filename.endswith(('.txt', '.py', '.java')):
        print('Are you trying to annoy me? How about giving me a TEXT or SOURCE CODE file, genius?')
        return

    with open(filename) as f:
        n_lines = 0
        n_words = 0
        for line in f:
            n_lines += 1
            n_words += len(line.split())
    print('Your file has {} lines, and {} words'.format(n_lines, n_words))
@END

```
