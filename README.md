<div align="center">

## Basics of C/C\+\+ Part 6: Intro to Pointers


</div>

### Description

Welcome to the sixth in my series of tutorials. This is one about a topic that you may or may not have already heard about...pointers. What are they, what do they do, why do we care? First, why do we care. We care about pointers because they allow access to memory, the also make array-access faster, they are also somewhat necessary to understand some functions. Most importantly, you will see them a lot in other people's code. You may not need to use them much, but it will be tremendously important to understand them.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Alexander of CProgramming\.com](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/alexander-of-cprogramming-com.md)
**Level**          |Intermediate
**User Rating**    |3.3 (23 globes from 7 users)
**Compatibility**  |C, C\+\+ \(general\)
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__3-1.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/alexander-of-cprogramming-com-basics-of-c-c-part-6-intro-to-pointers__3-458/archive/master.zip)





### Source Code

<p><font face="Verdana">Second, what do they do. Well, I might as well address
this issue as well as what they are at the same time. Pointers are what they
sound like...pointers. They point to locations in memory. Picture this: a big
jar that holds one thing, the name of another jar. In the other jar is the value
of an integer. The jars are memory locations. The jar that holds the name of the
other jar is a pointer. It points to the other drawer.</font></p>
<p><font face="Verdana">     How can you use this? Well,
look at this little piece of code:</font></p>
<p><font face="Verdana">#include <iostream.h></font></p>
<p><font face="Verdana">void main()</font></p>
<p><font face="Verdana">{<br>
int x;<br>
int *pointer;<br>
<br>
pointer=&x;<br>
cin>>x;<br>
cout<<*pointer;</font></p>
<p><font face="Verdana">}</font></p>
<p><font face="Verdana">     Guess what! The cout outputs
the value in x. Why is that? Well, look at the code. The integer is called x.
Then a pointer to an integer is defined as pointer. The astrick(*) symbol means
that it is a pointer. Then I give the memory location of x to pointer by using
the ampersand(&) symbol. It gives the memory location of the variable it is
in front of. For example, if the jar that had an integer had a ampersand in it
it would output its name, or location.  Then the user inputs the value for
x. Then the cout uses the * to put the value stored in the memory location of
pointer. Huh? Picture the jars again. If the jar with the name of the other jar
in it had a * in front of it it would give the value stored in the jar with the
same name as the one in the jar with the name. It's not too hard, the * gives
the value in the location. The unastricked gives the memory location.</font></p>
<p><font face="Verdana">     I hope this has been at least
an interesting introduction to pointers. I do not suggest that you play around
with them too much as you can do unpleasant things on your computer, but you now
should have a better understand of what they are.</font></p>

