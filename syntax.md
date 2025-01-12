TextWarp



Main file / background (main.tw)
Each sprite has a folder, and file (sprite.tw)
Has both a console and visual output
Has the same syntax as python
Compatible with python files in console


Syntax:

Literally python syntax




File structure:

Main.tw
sprite_name.tw
/assets
/assets/main/
/assets/main/sounds/sound.extension
/assets/main/costumes/costume.extension
/assets/sprite_name/costumes/costume.png
Etc


Visual Commands:

From Scratch:

Motion (n/a in main.tw because the background can’t move):


Move(steps)
Turn(degrees)
Goto(sprite, mouse, random position)
Goto(x,y)
Glide(seconds)(sprite, mouse, random position, x, y, x and y)
pointat(sprite, mouse, random position, direction)
ChangeChord(x or y)(amount)
SetChord(x, y or x and y)(x, y or x and y)
Edgebounce(true, false)
RotationStyle(idek lol)


Looks:

say(“text”)(seconds)
think(“text”)(seconds)
Costume(name)
Nextcostume()
Backdrop(name)
BackdropWait()
Nextbackdrop()
Changesize(amount)
Size(%)
Show()
Hide()
Layer(front, back) or (- amount) or (+ amount) or (layernumber)

Sound:

I’m going to do sound differently, scratch sound sucks


Events:


OnStart()
OnKey()
OnClick()
OnBackdrop()
When()
OnMessage()

SendMessage()
SendMessageWait()

Control:

Wait(seconds)
Repeat(amount)(code)
Forever(code)
If()(then)(else)
WaitUntil()
Repeatuntil()(code)
StopScript()
Kill()

WhenClone(code)
CreateClone()
DeleteClone()


Sensing:

Ask(“text”) will be made obsolete by my new text functionality 
DragMode(1 or 0)
Timer(stop) or (start) or (reset)

Variables:

Set(variable)(value)
Change(variable)(value)

ShowVar(variable) will be made obsolete by my new text functionality 
HideVar(variable) will be made obsolete by my new text functionality

Lists:

ListAdd(thing)(list)
ListDelete(all, or thing)(list)
ListInsert(thing)(at)(list)
ListReplace(thing)(thing)(list)

Showlist(list) will be made obsolete by my new text functionality 
Hidelist(list) will be made obsolete by my new text functionality 

Custom Blocks:

Just functions lol


From TurboWarp:





New Visual commands:



Console Commands (Literally compatible with python):

Python Built In Commands:

abs()
all()
any()
ascii()
bin()
bool()
bytearray()
bytes()
callable()
chr()
classmethod()
compile()
complex()
delattr()
dict()
dir()
divmod()
enumerate()
eval()
exec()
filter()
float()
format()
frozenset()
getattr()
globals()
hasattr()
hash()
help()
hex()
id()
input()
int()
isinstance()
issubclass()
iter()
len()
list()
locals()
map()
max()
memoryview()
min()
next()
object()
oct()
open()
ord()
pow()
print()
property()
range()
repr()
reversed()
round()
set()
setattr()
slice()
sorted()
staticmethod()
str()
sum()
super()
tuple()
type()
vars()
zip()

Python String Methods:


Python list/array methods:

Python dictionary methods:

Python tuple methods:

count()
index()

Python set methods:

Python file methods:

Python Keywords:












