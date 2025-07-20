# Aneurisma
A cool like programing language, derived from apl and bf.
Aneurisma are created in Snap! visual programing language.
Aneurisma don't have comments.
Aneurisma have a memory(the general for of storage) and 50 cells (the second form of storage).
Aneurisma have the commands:
1."-x" subtract x from memory
2."⫰x'y" replace x with y in the code
3."←x'y" set the memory to the section x of line y
4."•" print memory like in bf
5."⨅x" Run x until memory are equal to the cell item of pointer
6."¤" set memory to 0
7."Ω" stop the program(not obrigatory)
8."&#9664;" set the memory to a list of correspondents unicodes of memory
9."&#x25B6;" inverse of &#9664;
10."↢x" set the memory to line x
11."⁕x" run code x (use _ to split code)
12."⁅" receive input and set the memory to it like in bf
13."⨭x" move x in cells
14."⨍" set memory to the cell of pointer
15."ʃ" inverse of ⨍
16."◡" run memory as Aneurisma code
17."⁖x" run x until the pointer item of cells is equal to 0 (like [] in bf)
18."ċx" convert binary x to decimal
29."ĉx" inverse of ċ
20."⫕" set memory to join the pointer item and the memory
21."⩋x'y'z" if memory = x, run y, else run z
22."⪦x" set ptr to x
23."⩡" pow operator, remove all zeroes of cells and add zeroes until the lenght of cells is 50
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
41."*x" multiply memory by x
42."^x" power memory by x
43."◐" half of memory
44."◔" a quarter of memory
45."<x'y" 1 if x are less than y
46.">x'y" 1 if x are greater than y
47."≡x" module of memory by x
48."ɦ" for each item in memory list, set the correspondent item of cells
49."◯" clear the output

the replacers are:
1.Δ  - The memory value
2.⩹  - The length of the line
3.⁞  - The last section
4.↓ - New line
5.– - Space
6.⨞  - The ptr
7.⨽  - Ptr of cells
8.⨼  - Ptr-1 of cells

Hello, World! program is:
 ⫰x'Hello,–World! x ←⁞'1 &#9664; • ¤

Cat program is:
 ⁅ • ¤

Quine program is:
 ↢1 ° •
