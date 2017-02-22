From: Scott Morrison <scott.morrison@anu.edu.au>

Dear all,

First --- this is a slight superset of people who came to the organisational meeting today. I'll remove you from the list if you're not interested.

We agreed to meet each week at 1pm on Wednesday, in the meeting room. We have it booked, and apparently most people are available, until 2:30pm, so we can run a bit long when we want to.

Everyone should start looking at the book <https://homotopytypetheory.org/book/>. There is also a course that was taught recently at Carnegie-Mellon which may be useful. Its webpage (including video lectures) is at <http://www.cs.cmu.edu/~rwh/courses/hott/>. The synopsis is helpful. Anyone else with useful resources can reply-all here to tell everyone about them!

Today:
* We scheduled our meetings! They'll usually be in the meeting room, except March 1, when we'll have to meet elsewhere.
* Mentioned that I started writing a note on setting up an interactive theorem proving environment for doing HoTT <https://github.com/semorrison/proof/blob/master/getting-started.md>. If someone wants to contribute instructions for setting up the HoTT library for Coq, that would be much appreciated. (Either email me, or even better, send a pull request on github!)
* Angus, Damon, and Rowan (is that correct??) "volunteered" to give us a crash course this Wednesday on the basics on algebraic topology for those who haven't seen any. They are respectively talking about \pi_1, \pi_2, and CW complexes. (Can someone else tell everyone what a fibration is, and what the path lifting property means?)
* Yao Fan volunteered to tell us a little about type theory itself, before we get to homotopy type theory, next Wednesday (March 1). You may like to try reading the first few chapters of "Programming in Martin-Löf's Type Theory" <http://www.cse.chalmers.se/research/group/logic/book/book.pdf>.
* We very informally talked about interpretations of type theory:
** in sets, where (a : A) means "a is an element of the set A", and X \to Y is the set of functions from the set X to the set Y.
** in propositions, where (a : A) means "a is a proof of the proposition A", and X \to Y is the proposition that X implies Y.
** in "homotopy types", which before HoTT had nothing to do with type theory.
* Someone may want to tell us all what the Curry-Howard isomorphism is (explaining the relationship between the first two interpretations)?
* We talked about a first example of a "higher inductive type", namely the circle S^1, which is "freely generated" by x : S^1, and p : ( x = x ), that is, it is a type which in "inhabited", i.e has a instance, and also has an nontrivial instance of the equality type x = x. Of course, x = x is already inhabited by "refl" (short for reflexivity; it is an axiom that for any x, it's equality type has an instance called refl_x). In the "types as homotopy types" interpretation, we interpret ( x = x ) as the type of paths from x to x.

best regards,
Scott
