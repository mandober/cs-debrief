# Formalism

In foundations of mathematics, philosophy of mathematics, and philosophy of logic, formalism is a theory that holds that statements of mathematics and logic can be considered to be statements about the consequences of certain string manipulation rules.

For example, Euclidean geometry can be considered a game whose play consists in moving around certain strings of symbols called axioms according to a set of rules called "rules of inference" to generate new strings. In playing this game one can "prove" that the Pythagorean theorem is valid because the string representing the Pythagorean theorem can be constructed using only the stated rules.


# Formal system

Formalization is the representation of deductive reasoning of a particular mathematical theory within an activity that is, in principle, driven exclusively by the form of statements disregarding their meaning.

Formalization turns mathematical theories into mathematical objects that we can study. This is analogous to building a model airplane with intention of studying through it the properties of a real airplane. One can also use the formal theory to generate theorems, i.e. discover truths in the real domain by simply running the simulation that this theory replica is.


---

A formal logical system is an organization of terms used for the analysis of deduction.

Components of formal systems:
- **Alphabet**
- **Language** over the alphabet to construct sentences
- **Deriving rules** for producing new sentences

Properties of formal systems:
* __Consistency__: no theorem of the system contradicts another.
* __Validity__: the system's rules of proof never allow a false inference from true premises.
* __Completeness__: if a formula is true, it can be proven i.e. it is a theorem of the system.
* __Soundness__: if a formula is a theorem of the system, it is true (converse of completeness).


# Logical form


**Formalization** is the representation of deductive reasoning of a particular mathematical theory within an activity that is, in principle, driven exclusively by the form of statements disregarding their meaning.

Formalization turns mathematical theories into mathematical objects that we can study. This is analogous to building a model airplane with intention of studying through it the properties of a real airplane. One can also use the formal theory to generate theorems, i.e. discover truths in the real domain by simply running the simulation that this theory replica is.

---

Logic is generally considered formal when it analyzes and represents the form of any valid argument type.

The form of an argument is displayed by representing its sentences in the formal grammar and symbolism of a logical language to make its content usable in formal inference.

Simply put, to formalize simply means to translate English sentences into the language of logic.

This is called showing the logical form of the argument.

It is necessary because indicative sentences of ordinary language show a considerable variety of form and complexity that makes their use in inference impractical.

It requires, first, ignoring those grammatical features irrelevant to logic (such as gender and declension, if the argument is in Latin), replacing conjunctions irrelevant to logic (such as "but") with logical conjunctions like "and" and replacing ambiguous, or alternative logical expressions ("any", "every", etc.) with expressions of a standard type (such as "all", or the universal quantifier ∀).

Second, certain parts of the sentence must be replaced with schematic letters. 

Thus, for example, the expression "all Ps are Qs" shows the logical form common to the sentences "all men are mortals", "all cats are carnivores", "all Greeks are philosophers", and so on.



## Judgment
In mathematical logic, a judgment or **assertion** is a statement or enunciation in the metalanguage.

For example, typical judgments in first-order logic would be that a string is a well-formed formula, or that a proposition is true. Similarly, a judgment may assert the occurrence of a free variable in an expression of the object language, or the provability of a proposition. In general, a judgment may be any inductively definable assertion in the metatheory.


Judgments are used in formalizing deduction systems:
- a logical axiom expresses a judgment,    
- premises of a rule of inference are formed as a sequence of judgments,    
- and their conclusion is a judgment as well   
  (thus, hypotheses and conclusions of proofs are judgments).


A characteristic feature of the variants of __Hilbert-style deduction systems__ is that the context is not changed in any of their rules of inference, while both __natural deduction__ and __sequent calculus__ contain some context-changing rules.

Thus, if we are interested only in the derivability of tautologies, not hypothetical judgments, then we can formalize the Hilbert-style deduction system in such a way that its rules of inference contain only judgments of a rather simple form.

The same cannot be done with the other two deductions systems: as context is changed in some of their rules of inferences, they cannot be formalized so that hypothetical judgments could be avoided—not even if we want to use them just for proving derivability of tautologies.

This basic diversity among the various calculi allows such difference, that the same basic thought (e.g. deduction theorem) must be proven as a metatheorem in Hilbert-style deduction system, while it can be declared explicitly as a rule of inference in natural deduction.

In type theory, some analogous notions are used as in mathematical logic, giving rise to connections between the two fields, e.g. Curry-Howard correspondence.

The abstraction in the notion of judgment in mathematical logic can be exploited also in foundation of type theory as well.



A **logical assertion** is a statement that asserts that a certain premise is true, and is useful for statements in proof. It is equivalent to a sequent with an empty antecedent.

For example, if $$p =\ \text{"x is even"}$$, the implication
$$(\vdash p) \to (x \pmod 2 \equiv 0)$$

is thus true. We can also write this using the logical assertion symbol:
$$\vdash ((\vdash p) \to (x \pmod 2 \equiv 0))$$

In computer programming and programming language semantics, these are used in the form of assertions; one example is a loop invariant.
