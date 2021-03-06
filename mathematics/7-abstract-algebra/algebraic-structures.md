# Algebraic structures

An *algebraic structure*, a structure on a *carrier* set, is a set of finitary operations on that underlying set.

A set with an additional structure is also called an *algebra*.

More complex structures (e.g. vector spaces, modules, algebras) can be defined by introducing multiple operations, different underlying sets or defining axioms.



The properties of specific algebraic structures are studied in **abstract algebra**. The general theory of algebraic structures has been formalized in **universal algebra**. The language of **category theory** is used to express and study relationships between different classes of algebraic and non-algebraic objects.

Some algebraic structures with one or more operations that obey a particular set of laws, have names.


## List of Algebraic Structures

Complex algebraic structures:
- vector spaces
- modules
- algebras


<details><summary>List of Algebraic Structures</summary><br>

* **Group-like**
  - Group
  - Abelian group
  - Semigroup
  - Monoid
  - Rack and quandle
  - Quasigroup and loop
  - Magma
  - Lie group
* **Ring-like**
  - Ring
  - Semiring
  - Near-ring
  - Commutative ring
  - Integral domain
  - Field Division ring
* **Lattice-like**
  - Lattice
  - Semilattice
  - Complemented lattice
  - Total order
  - Heyting algebra
  - Boolean algebra
* **Module-like**
  - Module Group with operators
  - Vector space
  - Linear algebra
* **Algebra-like**
  - Algebra
  - Associative 
  - Non-associative
  - Composition algebra
  - Lie algebra
  - Graded
  - Bialgebra

</details><br>



## Group
A group is an algebraic structure consisting of a set of elements equipped with an operation that combines any 2 elements to form a new group element, satisfying all 4 group axioms:
1. Closure
1. Associativity
1. Identity
1. Invertibility

## Abelian group
Abelian or a commutative group is a group that also satifies the axiom of commutativity, so the result of applying the group operation to two group elements does not depend on the application order. Abelian groups generalize the arithmetic of addition of integers.
1. Closure
1. Associativity
1. Identity
1. Invertibility
1. Commutativity

## Lattice
A lattice is an abstract structure consisting of a **poset** in which every two elements have a unique supremum (least upper bound or **join**) and a unique infimum (greatest lower bound or **meet**). An example is given by the natural numbers, partially ordered by divisibility, for which the unique supremum is the least common multiple and the unique infimum is the greatest common divisor.

### Field
A field is a set on which addition, subtraction, multiplication, and division are defined, and behave as the corresponding operations on rational and real numbers do. A field is thus a fundamental algebraic structure, which is widely used in algebra, number theory and many other areas of mathematics.

### Ordered field
In mathematics, an ordered field is a field together with a total ordering of its elements that is compatible with the field operations. Historically, the axiomatization of an ordered field was abstracted gradually from the real numbers, by mathematicians including David Hilbert, Otto Hölder and Hans Hahn.

### Lie group
In mathematics, a Lie group (pronounced "Lee") is a group that is also a differentiable manifold, with the property that the group operations are compatible with the smooth structure. Lie groups are named after Norwegian mathematician Sophus Lie, who laid the foundations of the theory of continuous transformation groups.

### Topological group
In mathematics, a topological group is a group G together with a topology on G such that the group's binary operation and the group's inverse function are continuous functions with respect to the topology. A topological group is a mathematical object with both an algebraic structure and a topological structure.


---

## Group-like structures

- **T**otality (closure is equivalent, but differently defined)
- **A**ssociativity
- **Id**entity
- **In**vertibility
- **C**ommutativity

| structtures       | T | A | Id | In |C|
|-------------------|---|---|---|---|--|
| Magma             | ✓  |    |    |    |  |
| Category          |    | ✓  | ✓  |    |  |
| Monoid            | ✓  | ✓  | ✓  |    |  |
| Loop              | ✓  |    | ✓  | ✓  |  |
| Semigroupoid      |    | ✓  |    |    |  |
| Groupoid          |    | ✓  | ✓  | ✓  |  |
| Quasigroup        | ✓  |    |    | ✓  |  |
| Semigroup         | ✓  | ✓  |    |    |  |
| Inverse Semigroup | ✓  | ✓  |    | ✓  |  |
| Group             | ✓  | ✓  | ✓  | ✓  | |
| Abelian group     | ✓  | ✓  | ✓  | ✓  |✓|


## Magma
Magma is a basic kind of algebraic structure, consisting of a set equipped with a single binary operation which must be closed over the set.

A magma is a set M matched with an operation, •, that sends any two elements a, b ∈ M to another element, a • b.

The symbol, •, is a general placeholder for a properly defined operation. To qualify as a magma, the set and operation (M, •) must satisfy the following requirement (known as the magma or closure axiom):

For all $$a, b$$ in $$M$$, the result of the operation $$a \cdot b$$ is also in $$M$$; in mathematical notation: 

$$\display{a,b \in M \implies a \cdot b\in M}$$

If $$\cdot$$ is instead a partial operation, then $$S$$ is called a *partial magma* or more often a *partial groupoid*.


## Semigroupoid
Semigroupoid (semicategory, naked category, precategory) is a partial algebra that satisfies the axioms for a small category, except possibly for the requirement that there be an identity at each object.

Semigroupoids generalize semigroups in the same way that small categories generalise monoids and groupoids generalize groups.


## Groupoid
Groupoid (Brandt `groupoi`, virtual group) generalizes the notion of group in several equivalent ways. A groupoid can be seen as:
- Group with a partial function replacing the binary operation
- Category in which every morphism is invertible.
