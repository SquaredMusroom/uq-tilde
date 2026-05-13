### list of variables that should be in standard library.
I'll use ~ character for some random value.

### Actual list

int - standard int32.\
    `int q = ~;`\
    `int q[] = int[~];`\
    `int q[] = {~,~,~,~};`

float - just float. Also can be double see [CVS](docs/CVS.md).\
    `float q = ~.~;`\
    `float q[] = float[~];`\
    `float q[] = {~.~,~.~,~.~,~.~};`

char - some unicode character.\
    `char q = "~";`\
    `char q[] = char[~];`\
    `char q[] = {"~","~","~","~"};`
> [!NOTE]
> you can use quotes or double quotes for characters or strings it really does not matter.

bool - just bool.\
    `bool q = ~;`\
    `bool q[] = bool[~];`\
    `bool q[] = {~,~,~,~};`
> [!NOTE]
> Maybe true and false are too long to type so we can add some dynamic typing. Something like this:
> false = 0
> true = 1

string - array of chars.\
    `string q = "~";`\
    `string q = {"~","~","~","~"};`\
    `string q = char[~];`\
    `string q[] = string[~];`\
    `string q[] = char[~,~];`\
    `string q[] = {"~~~~","~~~~","~~~~","~~~~"};`\
    *man this looks miserable.*

enum - that thing for making types.\
    `enum q = {~,~,~,~}`\
    `q u = q.~;`\
    `q u[] = q[~];`\
    `q u[] = {q.~,q.~,q.~,q.~};`

---

### intresting things

if you have ever used multi-dimensional array you probably saw this funny thing:\
    `q[~][~] = ~;`\
but it doesn't look very good. So why don't we try this:\
    `q[~:~] = ~;`\
Of course it's only matter of taste.

And yeah there are vectors and other types but they are more specific so they should be implemented in other library. 
*Ah following the path of c# here. Well I haven't even used System.Numerics because guess what? Vectors are implemented in unity. So no faults on my side.*
