# Liam O'Brien
## Developer, Programmer, Computer Scientist

You can visit [my portfolio](file:///C:/Users/chuck/Documents/COGS%203/final_portfolio/O'Brienindex.html) to see my past work (I have one on my computer but no site hosting it). 

### Front-End

I have used:

1. HTML
2. CSS
3. JavaScript
4. Bootstrap
5. Figma
   - Most of these I learned or revisited in COGS 3

### Back-End

I have used:

- C
- C++
- Java
- Verilog

- [x] CSE 11
- [x] CSE 12
- [x] CSE 20/21
- [x] CSE 30
- [x] CSE 100
- [x] CSE 101
- [ ] CSE 110
- [ ] CSE 130
- [x] CSE 140/140L
- [ ] CSE 141/141L

### Developing Algorithms

I have learned many techniques such as Backtracing, Dynamic Programming, and Greedy Algorithms.

#### Example Algorithm

```markdown

Problem: Least Amount of Damage to get from Column 1 to Column n.
Given a n x n matrix filled with damage values at each cell.
Step 1: Let M[i,j]M[i,j] be the minimum amount of damage to get from the left column to cell (i,j)(i,j) (including the damage from cell (i,j)(i,j)).
Step 2: Base Cases: M[i][1] = A[i][1] for all i >= 1.
Step 3: Recursion: Three Cases, Three directions to travel from:
Up-Right: M[i][j] = M[i+1][j-1] + A[i][j] only if i+1 <= n and j-1 >= 1
Right: M[i][j] = M[i][j-1] + A[i][j] only if j-1 >= 1
Down-Right: M[i][j] = M[i-1][j-1] + A[i][j] only if i-1 >= 1 and j-1 >= 1
Take minimum of all 3 since you don't know until you calculate.
M[i][j] = Min(M[i+1][j-1] + A[i][j], M[i][j-1] + A[i][j], M[i-1][j-1] + A[i][j])
Step 4: Order of problems: Vertical slices, left to right
Step 5: Output = Min( M[i][n] ) where i goes from 1 to n.

```

### Important Algorithms

I have studied _important_ and _vastly_ used algorithms such as **BFS/DFS, Huffman Encoding, Quicksort, Graphsearch, and more.**

I'd probably put a picture of some front-end stuff here if this was a serious site.

### About me:

I really like pasta, especially mac n cheese, pizza, and wings.

My favorite quote is from Albert Einstein:

>Two things are infinite: the universe and human stupidity; and I'm not sure about the universe.

![Mac n Cheese](https://www.momontimeout.com/wp-content/uploads/2018/10/homemade-mac-and-cheese-recipe-titled.jpg)

I'm good at talking with people and working together on group projects. Especially with people that I have gotten to know.

Thank you for taking the time to read my webpage!

And thank you @chauvu (idk her github name) for helping me!

:hugs:
