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

```js
// TABLE MENU
console.log("@1 [DATA]");
console.log("  print 'preservation of DATA'");
console.log("\nDATA: relay patch msg: networker\n");

console.log("@2 [META]");
console.log("  print 'preservation of META TAGS' '<pre>' '<code>' 'import link command'");
console.log("\ncase: while (true) {");

const systemCommands = [
  'system::model',
  'system::patch',
  'system::connect',
  'system::network',
  'system::relay',
  'system::configuration',
  'system::settings'
];

systemCommands.forEach(command => console.log(`  '${command}'`));

console.log("}\n");

console.log("@3 [BUILD]");
console.log("  + application build");
console.log("  + other details included");
console.log("  + etc.");

console.log("@4 [UPDATE]");
console.log("  + Any and all fixes related to the project");
console.log("\n    A.) test make a file");
console.log("    B.) test via command line tools\n");

// Project Details
console.log("## Project Details");
console.log("To design an application that can serve as a foundation.");
console.log("Each test case is a test for patching issues.");
console.log("\ncommand[ ./b./t./c./command. ]\n");

console.log("+ A.) test case");
console.log("+ B.) retry what doesn't work");
console.log("+ C.) doing it right the first time around -- slow down coding\n");

// Project Specs For Installation
console.log("## Project Specs For Installation");
console.log("npm project build");
console.log("npm install build project");
console.log("npm install command toolset\n");

console.log("@BEGIN SYS.caller-project");
console.log("import system;");
console.log("return 0;");
console.log("return 1;");
console.log("-- KEY BLOCK --");
console.log("import system from os1;");
console.log("use strict;");
console.log("use warnings;");
console.log("qw('readonly DATA')");
console.log("-- INNER MESSAGE --");
console.log("<!doctype html>");
console.log("<pre>");
console.log("<code>");
console.log("abcdefghijklmnopqrstuvwxyz");
console.log("acegikmoqsuwyzxvtrpnljhfdb");
console.log("qazwsxedcrfvtgbyhnujmikolp");
console.log("qwertyuiopasdfghjklzxcvbnm");
console.log("</code>");
console.log("</pre>");
console.log("-- END INNER MESSAGE --");
console.log("-- BLOCK END --");

// Networker
console.log("## Networker");
console.log("// add additional DATA here.");
console.log("?");

console.log("from tkinter import *;");
console.log("from easygui import fileopenbox;\n");

console.log("const root = Tk();");
console.log("root.title('Word Counter');");
console.log("root.geometry('500x500');\n");

console.log("const app = Frame(root);");
console.log("app.grid();");
console.log("const button1 = Button(app, 'Browse for a file');");
console.log("button1.grid();\n");

console.log("const button2 = Button(app);");
console.log("button2.grid();");
console.log("button2.configure('Count the file');\n");

console.log("const button3 = Button(app);");
console.log("button3.grid();");
console.log("button3.text = 'Exit';\n");

console.log("root.mainloop();\n");

console.log("function wordCount(filename) {");
console.log("  filename = fileopenbox();");
console.log("  if (!filename.endsWith('.txt', '.py', '.java')) {");
console.log("    console.log('Are you trying to annoy me? How about giving me a TEXT or SOURCE CODE file, genius?');");
console.log("    return;");
console.log("  }\n");

console.log("  const lines = 0;");
console.log("  const words = 0;");
console.log("  for (const line of filename) {");
console.log("    lines += 1;");
console.log("    words += line.split(' ').length;");
console.log("  }\n");

console.log("  console.log('Your file has ' + lines + ' lines, and ' + words + ' words');");
console.log("}\n@END");

```
