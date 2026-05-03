<h5>uq~</h5>

> [!IMPORTANT]
> *BTW this is just a draft so don't expect anything*

---

So I want to make a programing language with syntax similar to c# and c++.<br>
And I don't want to use most of OOP's rules in this language because you can calmly live without them and they don't really look meaningful to me.<br>

| idea | description | status |
|------|-------------|--------|
| link | [link](docs/link.md)    | idk    |
| QSLN | [QSLN](docs/QSLN.md)    | idk    |
| Cint | Cint[^1]    | idk    |
| FIOL | FIOL[^2]    | idk    |
| Rgx  | Rgx[^3]     | idk    |

Roadmap:
- [ ] make normal documentation
- [ ] finish this
- [ ] write syntax
- [ ] finish documentation
- [ ] write translator/compiler

Abbreviations are great so there will be many of them.<br> The main point is that I don't want long lines in my language.<br> And if you ever written in c# you will understand what i mean by that.


[^1]: Custom int. Int with user defined amount of memory. Implementation is kinda hard because settings for ints doesn't really exist in c# and c++(Or if there is some I haven't seen them). 
[^2]: File input / output library(of course questionable name will be provided). C#'s IO library is ehm... lets say it's a little bit weird.<br> I mean may be I'm wrong but I don't think that typing: <br> `using (var stream = File.Open(fileName, FileMode.Create))
        {
            using (var writer = new BinaryWriter(stream, Encoding.UTF8, false))
            {
                writer.Write([something]);
            }
        }`<br> Is very convenient. <br> And if you didn't know that this funny thing exists that's totaly fine. 
[^3]: Something like regex. Recently I heard that c#'s LINQ is basically regex and guess what I heard that regex is cool and that it is used in some huge databases or something like this. 
