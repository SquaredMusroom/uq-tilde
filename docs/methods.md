## Methods || functions

---

very simple expressions nothing new.

`p t na(args)`\
`{`\
`    ~;`\
`    return rv;`\
`}`\
Where 
p is parameters like `public , private etc...`. Also can be left empety\
t is type that must be returned can be void if method shouldn't return anything\
na is name of method. It is recomended to use abriviatin for name to avoid long lines\
~ is some code.\
and rv is value that will be returned.
> [!NOTE]
> list of parameters will be provided later in other file\
> It is not necessary but youprobably should add a comment after arguments containing full name of method 

### Examples

`var AV(var u,var q) //Add variable`\
`{`\
`    return u+q;`\
`}`\
and to use it you need to type something like this:\
`var s = AV('ae',8);`

`void beer()`\
`{`\
`   wrl('good evening moonshiners');`\
`}`

wrl here means writeline and may be included in standard library.

