### Custom variable sizes 

> [!NOTE]
> Gah daumn I just realized that this is identical to int32 and others.
> Hmm you know what? I don't care it should exist anyway.

> [!IMPORTANT]
> maybe this feature will be too problematic to make so don't get your hopes up about this.

Some funny syntax for setting variable size. I'll use "#" character for this feature.

How this should look:  
    `type#~ q;`  
where type is some variable type and "~" character is some value.

#### Examples

oh by the way do you remember what I said about double beeing float. Here it is:\
    `float#64 q;`\
of course if you think that double should take 64 bits.

and here is typical int64:\
    `int#64 q;`\

But there is a problem. How do we set size for strings. Well I don't know maybe we can just agree that this:\
    `string#~ q;`\
is identical to this:\
    `string q[] = char[~];`\

> [!NOTE]
> man who will even use this?
