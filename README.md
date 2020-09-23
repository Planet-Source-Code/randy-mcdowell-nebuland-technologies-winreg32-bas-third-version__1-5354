<div align="center">

## WINREG32\.BAS \(Third Version\)


</div>

### Description

This time I got it right!

In the last release I discovered a few errors, so I took

my time on this one to re-write every little piece of

code, using my old module as a building block. In this

version I added the 'OS' suffix to all the registry API

declarations so I could use 'Reg' in my function names.

Now all Subs are Functions, and return some type of

value, depending on the procedure. In this version I

also added the ability to save a string to a binary

key (RegWriteExtended), which was requested. Also error

checking has been revised and the RegLastError variable

always contains the last registry error that occured.

If you modify this code please send me a copy so I can

learn from what you have done. I hold absolutely no

warranties on this code and I am not responsible for

any damage it does to your registry or your computer.
 
### More Info
 
Always backup your system registry (the hidden SYSTEM.DAT file in your windows directory) before making any modifications to it. Like I stated before, I am not responsible for any damage you cause.


<span>             |<span>
---                |---
**Submitted On**   |2000-01-06 23:54:56
**By**             |[Randy Mcdowell \(Nebuland Technologies\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/randy-mcdowell-nebuland-technologies.md)
**Level**          |Advanced
**User Rating**    |4.7 (61 globes from 13 users)
**Compatibility**  |VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Registry](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/registry__1-36.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[CODE\_UPLOAD2761172000\.zip](https://github.com/Planet-Source-Code/randy-mcdowell-nebuland-technologies-winreg32-bas-third-version__1-5354/archive/master.zip)








