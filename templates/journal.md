# Lisa's Technical Journal

## Week Two (1/30 to 2/6)

Hour 1-2: downloaded and installed Homebrew and then Jekyll from command line

Hour 3-4: cloned lab files and wrote goals, successfully pushed to github

Hour 4-5: class readings

Hour 6: tried to update journal and push via command line with no luck. Did everything with the template files over in class lab

* * *

## Week Three (2/7-2/13)

Hour 1-2 Reading abut plain text, working through first two exercises in LPtHW; ran into problems with exercise one (printing).

Discovered that Python 3 is running because I need both on my computer and looked up on Stack Overflow how to set things up so I can invoke one or the other in terminal. See answer below:

IMHO, the best way to use two different Python versions on macOS is via homebrew. After installing homebrew on macOS, run the commands below on your terminal. brew install python@2 brew install python Now you can run Python 2.7 by invoking python2 or Python 3 by invoking python3. In addition to this, you can use virtualenv or pyenv to manage different versions of python environments. I have never personally used miniconda but from the documentation, it looks like it is similar to using pip and virtualenv in combination. • 1 how does one install things for python2 now? – Charlie Parker Dec 8 '17 at 17:05 • pip2 install <package_name> – forevergenin Oct 24 '18 at 11:15

That worked but I am still running into the same error msg.

(base) Felis-Felix:pypractice me$ python ex11.py   File "ex11.py", line 1     print "Hello World!"                        ^ SyntaxError: Missing parentheses in call to 'print'. Did you mean print("Hello World!")? (base) Felis-Felix:pypractice me$ 

Tried all kinds of variations, didn't make a diff. Finally got it right - have to call up python2 in command to print file!

Hour 3 Working through exercises in LPtHW Ex 2: VS Code:

A comment, this is so I can read my program notes.
anything after the octothorpe is ignored by python.
print "I could have code like this." -#you can also yse the # to disable a piece of code.
print "this won't run."
print "this will run."
Terminal: (base) Felis-Felix:~ me$ source /Users/me/anaconda3/bin/activate (base) Felis-Felix:~ me$ conda activate base (base) Felis-Felix:~ me$ cd projects (base) Felis-Felix:projects me$ cd pypractice (base) Felis-Felix:pypractice me$ python2 ex2.py I could have code like this. this will run.

Ex 3 had a lot of syntax errors but finally got it

print "I will now count my chickens:"

the + adds 25 and 30 and the / divides by 6
print "Hens", 25 + 30 / 6

75 x 3 and I don't understand how the modulus operates in this equation
print "Roosters", 100 - 25 * 3 % 4 print "Now I will count the eggs:" print 3 + 2 + 1 - 5 + 4 % 2 - 1 / 4 + 6 print "Is it true that 3 + 2 < 5 - 7?" print 3 + 2 < 5 - 7 print "What is 3 + 2?", 3 + 2 print "What is 5 - 7?", 5 - 7 print "Oh that's why it's False." print "How about some more." print "is it greater?", 5 > -2 print "is it greater or equal?", 5 >= -2 print "is it less or equal?" , 5 <= -2

(base) Felis-Felix:pypractice me$ python2 ex3.py I will now count my chickens: Hens 30 Roosters 97 Now I will count the eggs: 7 Is it true that 3 + 2 < 5 - 7? False What is 3 + 2? 5 What is 5 - 7? -2 Oh that's why it's False. How about some more. is it greater? True is it greater or equal? True is it less or equal? False (base) Felis-Felix:pypractice me$
Hour 4 trying to update file on github via terminal, having trouble again!

## Week Four (2/13 to 2/20)

Hour 1: This week's readings..
Hour 2: Did lessons 4 and 5 in LPtHW. I'd like to dive into the study drill in ex. 5 for converting number variables into metrics but that could be a rabbit hole that I don't have time for right now
Hour 3-4: Updated journal and goals and pushing to Github with many of the same issues as last week.

Note: I got pretty sick on Thursday 2/14 and my mental focus is just returning today, on 2/19, so I wasn't able to practice as much as I'd wanted to this week.

## Week Five 2/20-2/27

Hour 1.5:  Practiced with html (at work) by importing sloth website to work computer and figuring out how to edit path to new location in the files/text. Obvious but took me awhile to figure out I couldn't do it in the web inspector window and had to do it in a text editor (I downloaded VS code). At home, read and thought through the GCDRI lesson on html/css (downloaded from github). 

Hour1.5- 2: caught up on last week's reading, A Web for Everyone. I am familiar with personas because I needed to use that strategy in my ITP project abtract/final paper a couple of years ago. However, I want to study the personas used for accessibility. 

Hour 3: Worked through lessons 6 and 7 in LPtHW
hour 4: readings for this week
Didn't practice enough

