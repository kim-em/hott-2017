# hott-2017
Homotopy type theory reading group at ANU, 2017

Plans
---

* Florrie will give us a crash course on type theory on Wednesday March 1.
* Max will explain to us what a fibration is, and what the path lifting property is.

Requests
---

* What is the Curry-Howard isomorphism?
* What does the univalence axiom say?

Resources
---

* The [Homotopy type theory book](https://homotopytypetheory.org/book/).
* A [course on HoTT at Carnegie-Mellon](http://www.cs.cmu.edu/~rwh/courses/hott/), including video lectures.
* We will put up notes from each week's discussion here. Anyone who has notes, either handwritten or TeX'd can contribute them.
    * Week 1
        * [the email summarising the organisational meeting](https://github.com/semorrison/hott-2017/blob/master/notes/week-1/organisational-meeting.md)
        * [notes from Feb 22](https://github.com/semorrison/hott-2017/blob/master/notes/week-1/2017-02-22_algebraic-topology.pdf); a crash course in algebraic topology.
* To add content or files here, either
    * send them to Scott,
    * create a github account and ask Scott for commit access, 
    * create a github account and create a pull request, or
    * you can use the online LaTeX editor at SageMathCloud, which we've [hooked up to this repository](https://cloud.sagemath.com/projects/73ac273c-acff-45e1-b1ab-c4e55ae33e5f/files/hott-2017/). You'll need to create an account there and ask for access. Please remember to `git push` your changes from the SageMath terminal.
* Let's try using the issues page here on github to keep track of questions we'd like to collectively think about. Scott has put up a first example, about the space of proofs that fg = gf in \pi_2(X). Please feel free to put anything up here, including basic questions asking for clarifications.

Interactive theorem proving
---

Homotopy type theorists like to use computer proof assistants (aka interactive theorem provers). The options are essentially
* Coq,
* [Lean](https://leanprover.github.io/) ([installation hints](https://github.com/semorrison/proof/blob/master/getting-started.md)), and
* Agda.

Coq is probably the best option for now. It is easy to install, but we need someone to also install the HoTT library, and then explain to all of us how to do that. Please send Scott an email (or even better a pull request here)!

(Agda is apparently less pleasant to use. Lean has some great features --- please talk to Scott if you're interested in learning Lean! --- but currently support for homotopy type theory is broken.)
