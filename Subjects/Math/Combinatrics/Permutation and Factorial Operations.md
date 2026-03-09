You Might have seen $n!$ but do you know what it means?
[[Math MOC]]
[[Independent Operations]]

## Factorial

A Factorial is a function, only able to  be applied on natural numbers ($1,2,3\dots \in \mathbb{N}$). It Multiplies all natural numbers upto the number itself, including that number. For example: $$
3! = 1 \times 2 \times 3
$$
$$
10! = 1 \times 2 \times \dots 10
$$

## Arranging Items as permutation

Lets say you have 10 items, labeled, 01 to 10. How many Different ways are there to arrange the items?

To solve this, lets imagine there are 10 slots on a line.

[ ] - [ ] - [ ] - [ ] - [ ].....

How many ways are there to fill the first slot?
> Well there are **10** beacuse there are 10 items

Wb The second slot?
> Now, since one item has been used, there are Nine more items, hence **9** ways

The Third?
> Same logic, **8**


And so on and so forth, and for the last slot, there is one item and only one way to fill in.


From what we learnt in [[Independent Operations]] :

, these ways of choosing an item for each slot are independant, just that the number of choices decreases by one every time. Hence, the total ways to arrange them is...
$$
10 \times 9 \times 8 \times \dots 1 
$$

#### Hey! That looks like the Factorial function!

Yes indeed, they are the same, so:

$$
10 \times 9 \times 8 \times \dots 1  = 10! = 3628800
$$
So, we can use factorial for these problems.

> [!Tip] Trivial example
> Bob has 5 paintings, how many different ways are there to arrange them.
> well,
> $$
5! = 120
>$$
>Hence, 120 ways



### Permute

Well, lets say bob has 8 paintings, but only 3 frames to place them in. How many different ways are there to choose and arrange them paintings when only 3 can be chosen?

Well, imagine 3 slots...

For the First slot
> Since there are 8 paintings, there are 8 ways to choose them.

For the second slot,
> Since There are 7 paintings, there are 7 to choose from

For the third and final slot,
> There are 6 to choose from

Anddddd we are donee.

so, the total ways of choosing is
$$
8 \times 7 \times 6 = 336
$$

Its really the first three (or last three, depending on how you look at it) of the factorial applied to 8.

There is a really nice function that brings this together.

$$

 ^{8}P_{3}=8 \times 7 \times 6=336
$$
Which is called **Permutation**

