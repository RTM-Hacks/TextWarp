『🔠』 •  TextWarp

• Main file / Background (main.tw)
• Each Sprite has a Folder, and File (sprite.tw)
• Has both a console and visual output
• Has the same syntax as Python
• Compatible with Python files in console


『🔢』 •  Syntax:

• Same as Python 


『🗂️』 •  File Structure:

main.tw
sprite_name.tw
/assets
/assets/main/
/assets/main/sounds/sound.extension
/assets/main/costumes/costume.extension
/assets/sprite_name/costumes/costume.png

etc.


『🧩』 •  Visual Commands:

『🐱』 •  From Scratch:

• Motion (N/A in main.tw because the background can’t move):


Move(steps)
Turn(degrees)
GoTo(sprite, mouse, random position)
GoTo(x,y)
Glide(seconds)(sprite, mouse, random position, x, y, x and y)
PointAt(sprite, mouse, random position, direction)
ChangeChord(x or y)(amount)
SetChord(x, y or x and y)(x, y or x and y)
EdgeBounce(true, false)
RotationStyle(idek lol)


• Looks:

Say(“text”)(seconds)
Think(“text”)(seconds)
Costume(name) (N/A in main.tw because the background doesn’t have costumes it has backdrops)
NextCostume() (N/A in main.tw because the background doesn’t have costumes it has backdrops)
Backdrop(name)
BackdropWait()
Nextbackdrop()
ChangeSize(amount) 
Size(%)
Show()
Hide()
Layer(front, back) or (- amount) or (+ amount) or (layernumber) (N/A in main.tw because the background is the background)

• Sound:

I’m going to do sound differently, scratch sound sucks


• Events:


OnStart(code)
OnKey(key)(code)
OnClick(code)
OnBackdrop(backdrop)(code)
When(thing)(code)
OnMessage(message)(code)

SendMessage(message)
SendMessageWait(message)

• Control:

Wait(seconds)
Repeat(amount)(code)
Forever(code)
If()(then)(else)
WaitUntil()
RepeatUntil()(code)
StopScript()
Kill()

WhenClone(code) 
CreateClone()
DeleteClone()


• Sensing:

Ask(“text”) will be made obsolete by my new text functionality 
DragMode(1 or 0)
Timer(stop) or (start) or (reset)

• Variables:

Set(variable)(value)
Change(variable)(value)

ShowVar(variable) will be made obsolete by my new text functionality 
HideVar(variable) will be made obsolete by my new text functionality

• Lists:

ListAdd(thing)(list)
ListDelete(all, or thing)(list)
ListInsert(thing)(at)(list)
ListReplace(thing)(thing)(list)

Showlist(list) will be made obsolete by my new text functionality 
Hidelist(list) will be made obsolete by my new text functionality 

• Custom Blocks:

Functions


『🏎️』 •  From TurboWarp:



『🎨』 •  New Visual Commands:



『⌨️』 •  Console Commands (Compatible with Python):



『🐍』 •  Python Built In Commands:

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

• Python String Methods:

• Python List/Array Methods:

• Python Dictionary Methods:

• Python Tuple Methods:

count()
index()

• Python Set Methods:

• Python File Methods:

• Python Keywords:












