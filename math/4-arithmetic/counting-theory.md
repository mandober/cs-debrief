# Counting theory

The mathematical theory of counting is also known as *combinatorial analysis*.

Counting theory includes:
- fundamental counting rules
- permutation rule
- combination rule

Fundamental counting principles
- The rule of sum
- The rule of product
- Inclusion–exclusion principle 
- Bijective proofs
- Pigeonhole principle
- Method of distinguished element
- Generating function
- Recurrence relations

In mathematics, the essence of counting a set and finding a result n, is that it establishes a one-to-one correspondence (or bijection) of the set with the set of numbers {1, 2, ..., n}. A fundamental fact, which can be proved by mathematical induction, is that no bijection can exist between {1, 2, ..., n} and {1, 2, ..., m} unless n = m; this fact (together with the fact that two bijections can be composed to give another bijection) ensures that counting the same set in different ways can never result in different numbers (unless an error is made). This is the fundamental mathematical theorem that gives counting its purpose; however you count a (finite) set, the answer is the same. In a broader context, the theorem is an example of a theorem in the mathematical field of (finite) combinatorics—hence (finite) combinatorics is sometimes referred to as "the mathematics of counting."

Many sets that arise in mathematics do not allow a bijection to be established with {1, 2, ..., n} for any natural number n; these are called infinite sets, while those sets for which such a bijection does exist (for some n) are called finite sets. Infinite sets cannot be counted in the usual sense; for one thing, the mathematical theorems which underlie this usual sense for finite sets are false for infinite sets. Furthermore, different definitions of the concepts in terms of which these theorems are stated, while equivalent for finite sets, are inequivalent in the context of infinite sets.

The notion of counting may be extended to them in the sense of establishing (the existence of) a bijection with some well-understood set. For instance, if a set can be brought into bijection with the set of all natural numbers, then it is called "countably infinite." This kind of counting differs in a fundamental way from counting of finite sets, in that adding new elements to a set does not necessarily increase its size, because the possibility of a bijection with the original set is not excluded. For instance, the set of all integers (including negative numbers) can be brought into bijection with the set of natural numbers, and even seemingly much larger sets like that of all finite sequences of rational numbers are still (only) countably infinite. Nevertheless, there are sets, such as the set of real numbers, that can be shown to be "too large" to admit a bijection with the natural numbers, and these sets are called "uncountable." Sets for which there exists a bijection between them are said to have the same cardinality, and in the most general sense counting a set can be taken to mean determining its cardinality. Beyond the cardinalities given by each of the natural numbers, there is an infinite hierarchy of infinite cardinalities, although only very few such cardinalities occur in ordinary mathematics (that is, outside set theory that explicitly studies possible cardinalities).

Counting, mostly of finite sets, has various applications in mathematics. One important principle is that if two sets X and Y have the same finite number of elements, and a function f: X → Y is known to be injective, then it is also surjective, and vice versa. A related fact is known as the pigeonhole principle, which states that if two sets X and Y have finite numbers of elements n and m with n > m, then any map f: X → Y is not injective (so there exist two distinct elements of X that f sends to the same element of Y); this follows from the former principle, since if f were injective, then so would its restriction to a strict subset S of X with m elements, which restriction would then be surjective, contradicting the fact that for x in X outside S, f(x) cannot be in the image of the restriction. Similar counting arguments can prove the existence of certain objects without explicitly providing an example. In the case of infinite sets this can even apply in situations where it is impossible to give an example.[citation needed]

The domain of enumerative combinatorics deals with computing the number of elements of finite sets, without actually counting them; the latter usually being impossible because infinite families of finite sets are considered at once, such as the set of permutations of {1, 2, ..., n} for any natural number n.



## Fundamental Counting Rules


### The rule of sum
The rule of sum or __addition principle__ states that if there are $$x$$ possible outcomes for an event and $$y$$ possible outcomes for another event, and the two events cannot occur at the same time, then there are $$x + y$$ total possible outcomes for these events.

In terms of set theory, it states that sum of the sizes of a finite collection of disjoint sets is the size of the union of these sets: if $$S_1, S_2,\dots, S_n$$ are disjoint sets, then $$|S_1| + |S_2| + \dots +|S_n| = |S_1\cup S_2\cup \cdots \cup S_n|$$


### The rule of product
The rule of product or **multiplication principle** is also known as the **fundamental counting principle**.

It states that if there are $$x$$ ways of doing something and $$y$$ ways of doing another thing, then there are $$x · y$$ ways of performing both actions.

Generally, if there are $$x_1, x_2, \dots , x_n$$ number of ways of performing $$n$$ number of independent events separately, then the total unique ways by which all of them can be performed together will be the product: $$x_1 · x_2 · x_3 · (\dots ) · x_n$$.


### The inclusion–exclusion principle
This rule relates the size of the union of overlapping sets with their individual sizes and the size of their intersection.

The name comes from the idea that the principle is based on over-generous inclusion, followed by compensating exclusion.

It states that the number of elements in the union of sets $$A$$ and $$B$$ is equal to the sum of the number of elements in $$A$$ and $$B$$, minus the number of elements in their intersection, $$|A \cup B| = |A| + |B| - |A\cap B|$$


### Bijective proof
Bijective proof is a proof technique that finds a bijective function, $$f: A \to B$$, between two finite sets $$A$$ and $$B$$ (or a size-preserving bijective function between two combinatorial classes) thus proving that they have the same number of elements, $$|A| = |B|$$.

This technique is used to determine the size of a set that offers no direct way to count its elements. In such case, we can establish a bijection from such set $$A$$ to a more easily enumerable set $$B$$.


### Pigeonhole principle
The pigeonhole principle often ascertains the existence of something or is used to determine the minimum or maximum number of something in a discrete context. 

It states that if $$a$$ items are each put into one of $$b$$ boxes, where $$a \gt b$$, then one of the boxes contains more than one item.

The formal statement is that there does not exist an injective function whose codomain is smaller than its domain.

Using this one can, for example, demonstrate the existence of some element in a set with some specific properties. Or to demonstrate possibly unexpected results, e.g. that there is above 50% probability that two persons share the same birthday in a group of 23 people.


### Method of distinguished element
The method of distinguished element singles out a "distinguished element" of a set to prove some result.

In the mathematical field of enumerative combinatorics, identities are sometimes established by arguments that rely on singling out one "distinguished element" of a set.

Double counting is a technique that equates two expressions that count the size of a set in two ways.

Many combinatorial identities arise from double counting methods or the method of distinguished element. 


### Generating functions
Generating functions and recurrence relations are powerful tools that can be used to manipulate sequences, and can describe if not resolve many combinatorial situations.

Generating functions can be thought of as polynomials with infinitely many terms whose coefficients correspond to terms of a sequence. This new representation of the sequence opens up new methods for finding identities and closed forms pertaining to certain sequences. 

### Recurrence relation
A recurrence relation defines each term of a sequence in terms of the preceding terms. Recurrence relations may lead to previously unknown properties of a sequence, but generally closed-form expressions for the terms of a sequence are more desired.
