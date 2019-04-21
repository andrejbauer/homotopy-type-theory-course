# Homotopy (type) theory

A doctoral course on homotopy theory and homotopy type theory given by
[Andrej Bauer](http://www.andrej.com) and [Jaka Smrekar](https://www.fmf.uni-lj.si/~smrekar/)
at the [Faculty of mathematics and Physics](http://www.fmf.uni-lj.si/), University of Ljubljana,
in the Spring of 2019.

In this course we first overview the basics of classical homotopy theory. Starting with
the notion of locally trivial bundles, we motivate the classical definitions of
fibrations, from which we proceed to identify the abstract strucure of Quillen model
categories. We consider chain complexes as an example of model categories, and build up
enough material to be able to understand the natural ambient for homotopy theory, namely
the simplicial sets.

In the second part we introduce homotopy type theory from the point of view of classical
homotopy theory, deliberately avoiding the connections between homotopy type theory and
computer science. The simplicial sets serve as the motivating model category from which we
extract the basic type-theoretic constructions. We then show how type theory can be used
to carry out homotopy-theoretic arguments abstractly and "synthetically". The fact that
any construction expressed in homotopy type theory is homotopy invariant is both a
blessing and a curse: a blessing because it never lets us step outside of the realm of
homotopy theory, and a curse because we it never lets us step outside of the realm of
homotopy theory.

## Course administration

We meet weekly on Tuesdays from 14:00 to 16:00 in lecture room 3.06 at the Mathematics
department.

There will be two take-home exams, one for each part of the course.

## Course outline

### Homotopy theory

####  Background & bundles

##### Background

* What does (a part of) math deal with?
* Distinguishing between objects: relax, distinguish, stiffen
* Homotopy theory as a natural domain of algebraic invariants
* Homotopy theory as means of rephrasing a geometric problem

#### Bundles

* Bundles are omnipresent
* Vector bundle and its frame bundle
* Bundles with structure group
* Principal bundles and classification
* Lifting properties
* Homotopization of bundles

####  Fibrations of topological spaces, and their classification

* Hurewicz fibrations; definition in terms of the right lifting property with respect to inclusions Z->Zx[0,1]
* Pullbacks and retracts of fibrations are fibrations
* Any map decomposes functorially as a composite of a SDR inclusion followed by fibration
* The concept of a lifting function
* The fibres of a fibration are homotopy equivalent
* Homotopy fibre
* Puppe sequence

####  Cofibrations & model structure

* Homotopy extension property, cofibration, Eckmann-Hilton duality
* Pushouts and retracts of cofibrations are cofibrations
* Any map decomposes functorially as a composite of a cofibration followed by a `trivial` fibration
* Quillen closed model category
* Model category on Top with homotopy equivalences, Hurewicz fibrations, and Hurewicz cofibrations

####  Loop spaces, suspensions and other gadgets

####  Chain complexes

####  Kan simplicial sets

### Homotopy type theory

#### Type theory (motivated by simplicial sets): `Π`, `Σ`

* Type theory as a theory of constructions
* The notion of a dependent type
* Types as sets, dependent types as families of sets
* Types as spaces, dependent types as fibrations
* Basic type-theoretic constructions:
    * dependent products
    * dependent sums
    * basic types `0`, `1`, `N`

#### Identity types as path objects

* Identity types as path objects
* Type-theoretic rules for identity types
* Validity of the rules in Kan simplicial sets
* Basic homotopy-theoretic constructions in terms of identity types:
    * the groupoid of paths
    * contractible spaces
* Iterated identity types

#### Truncations

* Propositions, sets, and h-levels
* Truncation as a type-theoretic construction
* Truncation as an operation on (Kan) simplicial sets
* The Curry-Howard correspondence (using propostional truncation)
* Basic homotopy-theoretic constructions in terms of truncation:
    * loop space vs. fundamental group
    * path-connectedness vs. contractibility
    * surjectivity vs. split epimorphism
* Whiteheads's principle

#### Synthetic homotopy theory

* Inductive types, examples
* Higher-inductive types (HITs)
* Examples: circle, interval, suspension
* Truncations as HITs

#### Univalence axiom

* The idea that equivalent structures are equal
* Type universes
* Univalence axiom
* Consequences of the univalence axiom

#### Applications of univalence: loop space, `π₁(S¹) = Z`

* The loop space of a pointed space
* The fundamental group of a pointed space
* Proof that `π₁(S¹) = Z`


## Literature and resources

* J. Davis & P. Kirk, [Lecture Notes in Algebraic Topology](http://www.indiana.edu/~jfdavis/teaching/m623/book.pdf) (Chapter 4)
* R. Piccinini, [Lectures on Homotopy Theory](https://www.sciencedirect.com/bookseries/north-holland-mathematics-studies/vol/171) (Chapter 2)
* M. Hovey, [Model categories](https://web.math.rochester.edu/people/faculty/doug/otherpapers/hovey-model-cats.pdf) (Chapters 1-3)
* A. Strom, [The homotopy category is a homotopy category](https://mathscinet.ams.org/mathscinet/search/publdoc.html?arg3=&co4=AND&co5=AND&co6=AND&co7=AND&dr=all&pg4=AUCN&pg5=TI&pg6=PC&pg7=ALLF&pg8=ET&r=1&review_format=html&s4=strom&s5=the%20homotopy%20category&s6=&s7=&s8=All&sort=Newest&vfpref=html&yearRangeFirst=&yearRangeSecond=&yrop=eq)
* P. G. Goerss & J. F. Jardine, [Simplicial homotopy theory](https://www.springer.com/us/book/9783034601887) (Chapters I and II)
* Univalent foundations program, [Homotopy type theory: Univalent foundations of mathematics](https://homotopytypetheory.org/book/)

## Additional literature
 * Daniel G. Quillen, [Homotopical algebra](https://www.springer.com/gp/book/9783540039143)
