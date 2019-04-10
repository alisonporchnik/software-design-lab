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

##Week Six 2/27-3/6

Hour 1-3 had a lot of trouble with Jekyll and directories and bundles, wouldn't serve. But after trying to solve via Stack Overflow and the Jekyll site uninstalling/installing I finally got it properly installed with the bundles and got a site up. I added a photo and will work with more html, css and liquid.
hours 3-5 did the readings on ethics. Didn't get back to Jekyll

##Week Seven 3/6-3/13
Hour 1-3: Spent some time working on adding to and debugging the little program we did in class, which would not operate quite right.  Will work on another one of my own whether or not I figure out the problem there.
I didn't figure it out. Spent more time comparing program to the one Patrick uploaded. Eventually I got it right. I want to put it on the Jekyll site but don't have time to figure that out right now. Maybe we need to go over that first?

Hour 4: I went through this week's reading/exercises and studied the code and the exxplanation. I have a very general understanding of the differences between those three programming paradigms and can see how they do things differently, but I wouldn't know where to start in writing any of those scripts on my own. Also, I can't quite get the definitions/terms down. Code terminology is its own thing and I haven't assimilated it yet. That seems to be part of the problem. It's the equivalent (to me) of reading about Turkish in a version of English that uses a bunch of contemporary idiomatic French words. (I have retained only a high-school level of French from the 1980s.) I feel like if I understood the coding idiom better I would understand the explanations and the logic more clearly.

I wish I'd had more time to practice this week. 

###Week Seven 3/13-3/20

Hour 1: I've been having some trouble with QGIS, which I use for another course. It crashes in the middle of something I'm doing that is not saveable, that I then have to begin doing all over again, or maps don't always render correctly. We have to use an older version of it, which requires Python 2.8, and since this is also the version native to my Mac and I've been working in Python 2 anyway in this course, I decided to delete Anaconda3 and Python3 from my applications just to keep things "cleaner" and also in the hope that the problems have been caused by QGIS getting confused somehow. I think I may have installed Python 2 in my Anaconda folder so that I could toggle between them, but I can't remember and I didn't check. I wanted to delete things from the command line because I trust it more than dragging to the trash (unlike on a PC, which also has an uninstall application). So, between what I've learned how to do in class,the help of the internet, and trying until I got things right, I was able to delete these application directories with the subdirs and files in them from my applications folder and my home directory (for anaconda), including another installation of anaconda3 that I must have installed higher up in the "my computer" folder (or whatever the equivalent is on a Mac) for the DH Institute a couple of years ago. It was a simple operation but I spent about 35 minutes on it figuring it out. I'm hoping this will eliminate some of the trouble I've been having, and then at some point I can install an updated version of QGIS and Python 3 on my laptop. Or else it will cause more trouble. We'll see.

Hour 2-3
Tried to modify the cafe.py script with minimal success. wanted to make it return a different response if the item isn't on the menu (not successful). I did get it to return an additional comment to end the transaction -- cost of the order (set cost) - successul. Still struggling a lot with understanding how to get Python to do things, even using Stack Overflow. Probably need to spend more time with Zed Shaw.

Hour 4 Planned to spend more time with Zed but discovered that I'd worked through all of the free lessons in LPtHW.  Also, removing Anaconda and Python 3 didn't fix my left-hand Command key issue, which cropped up after installing some new software for my classes this fall (but not sure which software).

##Week Eight
Nothing. Absolutely nothing.

##Week Nine
Hour 1-2 Working on the Flask megatutorial. Ran into problems at end of ch. 1 - a warning that I could not run a development server in a production environment and the microblog app wouldn't run. 

Felis-Felix:venv me$ flask run
 * Serving Flask app "microblog.py"
 * Environment: production
   WARNING: Do not use the development server in a production environment.
   Use a production WSGI server instead.
 * Debug mode: off
Usage: flask run [OPTIONS]
Error: Could not import "microblog".
So it's not generating a local host address for the environment. Maybe this is because it's a designated virtual environment? I will try running it in the microblog directory instead just to see.

Also, since the keyboard issue wasn't solved, I am reinstalling Anaconda with Python 3, since I need it to use the pirated copy of Learn Python the Hard Way. Nope - same problem. Hmmm.

Hour 3: reviewing Python glossary (wasn't very helpful - I need something that explains what things are and do in lay terms) and then attempted to the install MSQL database to do the tutorial on W3Schools but I am having trouble and don't really know what I'm doing. I may try a different tutorial.

Hour 4-5 worked more on trying to get the myql installation (per W3 Schools) to work but there are errors involving problems with caching passwords, or python even recognizing what mysql is when I try to import the connector. It's definitely installed - located in Anaconda's Python 3.7 folder - but Anaconda has SQLite too. If I search for MYSQL a window pops up and I can run it that way. I can't create a database on it for the tutorial though.
Thoroughly frustrated, and spending so much time with no progress doesn't help me, I just get so deep in the weeds it's hard for me to see how things are structured and how they function. The only thing I'm really improving at is working in the command line. That's fine and good, but I really need to understand programming languages better.

##Week Ten
Hours 1-2 researching potential platforms for the software project and communicating with group on Slack. Hopefully some SQLite lab practice Tuesday.
