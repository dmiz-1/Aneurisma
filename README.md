# Aneurisma
A cool like programing language, derived from apl, bf and thue. <br>
Aneurisma are created in Snap! visual programing language, have 71 commands and 14 replacers. <br> 
Aneurisma don't have comments. <br>
Aneurisma have a memory(the general for of storage) and 100 cells (the second form of storage). <br>

Aneurisma have the commands: <br>
1."-x" remove x from memory <br>
2."⫰x'y" replace x with y from the actual line+1 to end of script (inspired by thue)<br>
3."←x'y" set the memory of section x of line y <br>
4."•" print memory like in bf <br>
5."⨅x" Run x until memory are equal to the cell item of pointer <br>
6."¤" set memory to 0 <br>
7."Ω" stop the program(not obrigatory) <br>
8."```◀```" set the memory to a list of correspondents unicodes of memory <br>
9."```▶```" inverse of ```◀``` <br>
10."↢x" set the memory to line x <br>
11."⁕x" run code x (use _ to split code) <br>
12."⁅" receive input and set the memory to it like in bf <br>
13."⨭x" move x in cells <br>
14."⨍" set memory to the cell of pointer <br>
15."ʃ" inverse of ⨍ <br>
16."◡" run memory as Aneurisma code <br>
17."⁖x" run x until the pointer item of cells is equal to 0 (like [] in bf) <br>
18."ċx" convert binary x to decimal <br>
29."ĉx" inverse of ċ <br>
20."⫕" set memory to join ptr of cells and memory <br>
21."⩋x'y'z" if memory = x, run y, else run z <br>
22."⪦x" set ptr to x <br>
23."⩡" pow operator, it remove all zeros of the cells, join the non-zero values, move them to the start and put zeros until the cells length is equal to 20 <br>
24."⇄" invert cells <br>
25."⇋x" shift x item of cells with the ptr item of cells <br>
26."⨡x" split memory value by x <br>
27."⨐x" set memory to item x of cells <br>
28."Ⅱx" set line to x <br>
29."Ⅰx" jump to line index of x in code <br>
30."√" square root the memory <br>
31."⁀" ceiling the memory <br>
32."‿" floor the memory <br>
33."⁐" round the memory <br>
34."□" sign the memory <br>
35."=x'y" 1 if x = y <br>
36."≠x'y" inverse of = <br>
37."∥x'y" 1 if x or y are 1 (or operator) <br>
38."×x" 0 if x are 1 (not operator) <br>
39."&x'y" 1 if x and y are 1 (and operator) <br>
40."÷x" divide memory by x <br>
41."+x" add x to the memory <br>
42."*x" multiply memory by x <br>
43."^x" power memory by x <br>
44."½" half of memory <br>
45."⅓" a third of memory
46."◔" a quarter of memory <br>
47."⅟" signum of memory
48."<x'y" 1 if x are less than y <br>
49.">x'y" 1 if x are greater than y <br>
50."≡x" module of memory by x <br>
51."⊕" for each item in memory list, set the correspondent item of cells to item of memory list <br>
52."◯" clear the output <br>
53."∾" sine of memory <br>
54."≁" cosine of memory <br>
55."≀" tangent of memory <br>
56."†x" set the memory to numbers from memory to x <br>
57."⫖" set memory to join all non-zero values of cells <br>
58."⫓" like ⫖, but with spaces <br>
59."⩒" set all cells to 0 <br>
60."⋃" organizes memory from smallest to largest <br>
61."⋂" organizes memory from largest to smallest <br>
62."⫏x'y..." set memory to a list (split items with ') <br>
63."⩤x" set memory to get row x of list memory <br>
64."⩥x" set memory to get column x of list memory <br>
65."⨲x" remove item x of list memory <br>
66."⪫x" set memory to index of x of list memory <br>
67."⩨x'y" set memory to item x of row y <br>
68."⨪x'y" set memory to replace item x in list memory <br>
69."∂x" set memory to map code x for each item in list memory <br>
70."≎x'y" add x to index y in memory list <br>
71."↻x'y" run x y times (if y are null, run x forever) <br>

The replacers are: <br>
1.Δ  - The memory value <br>
2.⩹  - The length of the line <br>
3.⁞  - The last section executed <br>
4.↓  - New line <br>
5.–  - Space <br>
6.⨞  - The ptr <br>
7.⨽  - Ptr of cells <br>
8.⨼  - Ptr-1 of cells <br>
9.⨹  - Last item of list memory <br>
10.⨹ - First item of list memory <br>
11.⨻ - The length of list memory <br>
And 3 expecial for ∂:
12.i - The item
13.j - The index
14.k - The list

OBS: replace replace ▶ with the charter Black Right-Pointing Triangle and ◀ with Black Left-Pointing Triangle, <br>

Hello, World! program is: <br>
 ```⫏Hello,–World! ◀ • ¤```

Cat program is: <br>
 ```⁅ • ¤```

Quine program is: <br>
 ```↢1 ▶ • ¤```
