# Aneurisma <br>
A cool like programing language, derived from apl and bf. <br> <br>
Aneurisma are created in Snap! visual programing language and have 50 commands. <br> <br>
Aneurisma don't have comments. <br> <br>
Aneurisma have a memory(the general for of storage) and 50 cells (the second form of storage). <br> <br>

Aneurisma have the commands: <br>
1."-x" remove x from memory
2."⫰x'y" replace x with y in actual section to the last
3."←x'y" set the memory of section x of line y
4."•" print memory like in brainfuck
5."⨅x" Run x until memory are equal to the cell item of pointer
6."¤" set memory to 0
7."Ω" stop the program(not obrigatory)
8."◀" set the memory to a list of correspondents unicodes of memory
9."▶" inverse of ◀
10."↢x" set the memory to line x
11."⁕x" run code x (use _ to split code)
12."⁅" receive input and set the memory to it like in brainfuck
13."⨭x" move x in cells
14."⨍" set memory to the cell of pointer
15."ʃ" inverse of ⨍
16."◡" run memory as Aneurisma code
17."⁖x" run x until the pointer item of cells is equal to 0 (like [] in brainfuck)
18."ċx" convert binary x to decimal
29."ĉx" inverse of ċ
20."⫕x'y" set memory to join x and y
21."⩋x'y'z" if memory = x, run y, else run z
22."⪦x" set ptr to x
23."⩡" pow operator, it remove all zeros of the cells, join the non-zero values, move them to the start and put zeros until the cells length is equal to 20
24."⇄" invert cells
25."⇋x" shift x item of cells with the ptr item of cells
26."⨡x" split memory value by x
27."⨐x" set memory to item x of cells
28."Ⅱx" set line to x
29."Ⅰx" jump to line index of x in code
30."√" square root the memory
31."⁀" ceiling the memory
32."‿" floor the memory
33."⁐" round the memory
34."□" sign the memory
35."=x'y" 1 if x = y
36."≠x'y" inverse of =
37."∥" 1 if ptr of cells or memory are 1 (or operator)
38."×" 0 if memory are 1 (not operator)
39."&" 1 if ptr of cells and memory are 1 (and operator)
40."÷x" divide memory by x
41."+x" add x to the memory
42."*x" multiply memory by x
43."^x" power memory by x
44."◐" half of memory
45."◔" a quarter of memory
46."<x'y" 1 if x are less than y
47.">x'y" 1 if x are greater than y
48."≡x" module of memory by x
49."ɦ" for each item in memory list, set the correspondent item of cells
50."◯" clear the output
51."∿" sine of memory

the replacers are: <br>
1.Δ  - The memory value <br>
2.⩹  - The length of the line <br>
3.⁞  - The last section executed <br>
4.↓ - New line(\n) <br>
5.– - Space(\s) <br>
6.⨞  - The ptr <br>
7.⨽  - Ptr of cells <br>
8.⨼  - Ptr-1 of cells <br>

OBS: replace replace ▶ with the charter Black Right-Pointing Triangle and ◀ with Black Left-Pointing Triangle <br>

Hello, World! program is: <br>
 ```⫰x'Hello,–World! x ←⁞'1 ▶ • ¤```

Quine program is: <br>
 ```↢1 ◀ •```

Cat program is: <br>
 ```⁅ • ¤```
 ```⁅ • ¤```

Quine program is: <br>
 ```↢1 ▶ • ```
