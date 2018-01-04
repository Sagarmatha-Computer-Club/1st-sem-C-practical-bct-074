# C-programming - practical worksheet programs
## first semester - Batch - 2074 - BCT
***Especially for Sagarmatha Engineering college***

This repo contains C programs that need to be run on practical classes . These are the codes present in the sheets given during practical or the codes you have to write.

- Each sheets have corresponding `SHEET-N ` folder.
- The Questions given in sheet are named as `Q-N.C`
- The answers to *Write a program* are named as `Q-N-A.C`.

[Click me for note](#noted)
> The programs written are solely compatible in `Turbo C++`,*an old stupid program for today's world.* Hence program contains weird things like:

```C
    #include <conio.h>
    void main(){ 
        clrscr(); // what ??
        getch(); // To terminate the running program ??? LoL
    }

```

> Hence avoid using editors like `code::blocks,geany` which use compilers like `gcc`,`mingw`

## Edit
- If you really want to run it in such editors or use other compilers, While compiling/building avoid strict compile check flags like *`-Wall` in `gcc`*, 
> `gcc -o `~-Wall~ `"output-file" "file.c"`
- Omit `#include <conio.h>` *that won't work* ,
- Omit `getch()`,`clrscr()`;
- `void main()` works good if you remove **strict** flag.
- ***Even after doing all this, `TurboC++` gives different result while doing complex operator precedence problems like :***
`c = b++ - --a + ++a - --b + a * b` *LoL*
---
<a name="noted">*note*</a> :

- `N` represents number.
- `BCT` represents Bachelors in computer engineering (group).
