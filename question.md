# COMP8123



## Lesson 8

1.Define a function balance :: Ord a =>[a] -> Tree a that converts a list of increasingly ordered elements into a balanced search tree. Hint: first define a function that splits a list into two halves whose length differs by at most one.

```haskell
x halve xs = splitAt (length xs 'div' 2) xs

```

2.Given the definition mult = λx → (λy → x ∗ y), show how the evaluation of mult 3 4 can be broken down into four separate steps.

```haskell
// Using apply-by-name (outermost):

```

![image-20221211121854744](C:\Users\p2209473\AppData\Roaming\Typora\typora-user-images\image-20221211121854744.png)

 3.Using a list comprehension, define an expression fibs :: [Integer] that generates the infinite sequence of Fibonacci numbers
0, 1, 1, 2, 3, 5, 8, 13, 21, 34,...
Hint: make use of the library functions zip and tail. Note that Integer is the Haskell type of arbitrary-precision integers.

```haskell

```

4.Implement the breadth-first numbering by simulating lazy-evaluation in Python or Java.

```python

```

<img src="C:\Users\p2209473\AppData\Roaming\Typora\typora-user-images\image-20221211110941082.png" alt="image-20221211110941082"  />



## Lesson 10

1.Think about the right-association problem of the grammar, and find out how to solve it.

```

```

2.Implement a functional parser for JSON1, that at least supports the following types of
values:
1 objects (possibly nested),
2 numbers (integers using decimal digits),
3 strings (ASCII encoding, with "\n", "\t", "\"", "\\" support).
4 false, true, null.

The parser reads a JSON script from a string, and output the corresponding abstract syntax
tree, defined as a datatype (deriving Show).

```haskell

```

