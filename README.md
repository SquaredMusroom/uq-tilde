<h5>uq~</h5>

*BTW this is just a draft so don't expect anything*

---

So I want to make a programing language with syntax similar to c# and c++.<br>
And I don't want to use most of OOP's rules in this language because you can calmly live without them and they don't really look meaningful to me.<br>

| idea | description | status |
|------|-------------|--------|
| link | link[^1]    | idk    |
| QSLN | QSLN[^2]    | idk    |
| Cint | Cint[^3]    | idk    |
| FIOL | FIOL[^4]    | idk    |

Roadmap:
- Finish this  [ ]
- Write syntax [ ]
- Write translator/compiler [ ]

Abbreviations are great so there will be many of them.<br> The main point is that I don't want long lines in my language.<br> And if you ever written in c# you will understand what i mean by that.

[^1]: Array that will have a link to another array.<br> It should look like this:<br> `int s;` <br> `link u = s` <br> `u = 92` <br> And this will be identical to this: <br> `int s = 92`
[^2]: Questionable standart libraries names. I mean why no. Don't you think that typing `using uq~.chacha` is much greater than typing `using system.[library name]`.
[^3]: Custom int. Int with user defined amount of memory. Implementation is kinda hard because settings for ints doesn't really exist in c# and c++(Or if there is some I haven't seen them). 
[^4]: File input / output library(of course questionable name will be provided). C#'s IO library is ehm... lets say it's a little bit weird.<br> I mean may be I'm wrong but I don't think that typing: <br> `using (var stream = File.Open(fileName, FileMode.Create))
        {
            using (var writer = new BinaryWriter(stream, Encoding.UTF8, false))
            {
                writer.Write([something]);
            }
        }`<br> Is very convenient. <br> And if you didn't know that this funny thing exists that's totaly fine. 
