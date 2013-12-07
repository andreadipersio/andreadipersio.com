FP Complete IDE
================

Haskell is the first functional language (excluding SQL) I ever used,
I spent quite a lot of time trying to learn how to be productive in it,
unfortunately I am still far from being more than a Haskell beginner but 
I must say, every hour spent trying to figure out functors, monad, and recursive
patterns payed off in terms of programming knowledge.

If you know Haskell, you probably have heard of the Glasgow/Glorious Haskell Compiler,
or **GHC**. 
Not only GHC is a great pieace of software, it also come with one of the best REPL
you can lay your hand on: **GHCI**.

Being a VIM user, my flow is:

- Write code in VIM
- Switch to a TMUX panel running GHCI
- Load the module in GHCI
- Play with my code
- Iterate

The 'play with my code' part is very important while learning a new language, 
and Haskell offers a lot of feature that make this experience pleasant.

Recently I wrote an [article on decharm.com](http://devcharm.com/pages/13-start-haskell) listing a bunch
of resources I found of particolar interest for Haskell beginners.

[FP Complete](https://www.fpcomplete.com/) is one of the newest resource I stumbled upon,
and in my opinion is the best one to start with.

I discovered FP Complete while searching for tutorials,
[School Of Haskell](https://www.fpcomplete.com/school) is a collection of tutorials, spanning from 
basic to advanced stuff. 
Not only you can run all the code examples in the FP Complete IDE, you can also change them, playing
with the code. When I say *playing* I really mean it: you can write functions and the IDE will dispaly their signature in the bottom panel, along with suggestion.

If you write something like:

```haskell
len' (x:xs) = 1 + len' xs
```



