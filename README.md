Hello there! I use this account for personal projects but also for work. 
I like building things from math projects to everyday software.

At work, I'm an R&D engineer at [Heliax](https://heliax.dev/), currently, developing
core components for [Anoma](https://anoma.net/)'s web4 systems in
[Elixir](https://elixir-lang.org/) and [TypeScript](https://www.typescriptlang.org/).
I also review [Solidity](https://www.soliditylang.org/) smart contracts as part of
this gig. 

In my spare time, I'm learning [Lean](https://lean-lang.org/) and using
[Agda](https://agda.readthedocs.io/) for my HoTT constructions.
For AI-driven web apps, I use Elixir and [Phoenix](https://www.phoenixframework.org/).
Phoenix is a big reason I switched from Python to Elixir for building apps.
There's also [PaperShelf](https://github.com/jonaprieto/papershelf), the macOS PDF
reader and library manager I wish I'd had years ago.


<details>
<summary>In the works</summary>
  
I'm building [OATP](https://github.com/jonaprieto/oatp),
based on my earlier Haskell project, [online-atps](https://github.com/jonaprieto/oatp). 
Written in Lean 4, OATP has a REPL and CLI for interacting with automated theorem provers. 
It parses [TPTP](https://tptp.org), runs local and online provers, and provides reproducible
artifacts, diagnostics, and more.

Before I could build OATP, I had to develop some tooling. You might find it useful too.

[Grip](https://github.com/jonaprieto/lean-grip) is an efficient, graded, byte-oriented
parser-combinator library inspired by my friend's project,
[prim-parser](https://github.com/janmasrovira/prim-parser). 
The grade tracks input consumption, allowing recursive parsers to be structurally
terminating rather than marked `partial`.

Using Grip, I can parse
[TPTP](https://tptp.org) in
[grip-tptp](https://github.com/jonaprieto/lean-grip-tptp), and JSON in
[grip-json](https://github.com/jonaprieto/lean-grip-json).
Another thing I wanted for Grip is better error messages, so that's 
[grip-diagnostics](https://github.com/jonaprieto/lean-grip-diagnostics),
 easy to read parse errors. 

CLI? [optparse-applicative?](https://hackage.haskell.org/package/optparse-applicative) in Haskell?
I build [Argus](https://github.com/jonaprieto/lean-argus) to handle typed command-line
parsing. Flag values are Grip grammars, and both the help text and shell
completions come from one inspectable spec. OATP uses it.

For ANSI colours and styled text, I built
[termcolor](https://github.com/jonaprieto/lean-termcolor), with
[layout](https://github.com/jonaprieto/lean-termcolor-layout) (Unicode width,
wrapping, boxes),
[diagnostics](https://github.com/jonaprieto/lean-termcolor-diagnostics) (caret
spans, gutters), [widgets](https://github.com/jonaprieto/lean-termcolor-widgets)
(pure progress bars and spinners),
[terminal](https://github.com/jonaprieto/lean-termcolor-terminal) and
[repl](https://github.com/jonaprieto/lean-termcolor-repl), where only the last two
touch a real terminal, so pure consumers never link IO.

[calc-chat](https://github.com/jonaprieto/lean-calc-chat) is a demo of the
termcolor stack: a chat-shaped terminal calculator.

[precommit-lean](https://github.com/jonaprieto/precommit-lean) has shared hooks
for Lean style and module names, and an axiom audit that limits the accepted axioms
to `propext`, `Classical.choice` and `Quot.sound`. Quite opinionated. It also carries the
[/lean-format](https://github.com/jonaprieto/precommit-lean/blob/main/.claude/commands/lean-format.md)
command I run on every declaration. It only changes whitespace and compares
token streams to check that.

</details>

<details>
<summary>More (old) projects: Juvix, distributed systems, Agda and HoTT</summary>

I used to think [Haskell](https://www.haskell.org/) would become the next big language for me at least.
Now I think it is any theorem prover with general-purpose programming support and dependent
types. That is Lean 4, it could have been Agda, but AI simply pushed Lean so much, made it mainstream, that
it would be a mistake to not learn it, and it's really fun, actually! I still miss Agda-way of proving things,
  proof-term construction I mean.

On compilers, at [Heliax](https://heliax.dev/), I was one of the main contributors to
[the FP Juvix programming language](https://github.com/anoma/juvix) and the
maintainer of [juvix-docs](https://github.com/anoma/juvix-docs),
[vscode-juvix](https://github.com/anoma/vscode-juvix),
[juvix-stdlib](https://github.com/anoma/juvix-stdlib) and
[juvix-mode](https://github.com/anoma/juvix-mode), plus more that never got a
repo. I also created
[juvix-mkdocs](https://github.com/anoma/juvix-mkdocs) for literate documentation.
It is used for the
[Juvix FP tutorial](https://docs.juvix.org/latest/tutorials/learn.html#data-types-and-functions).

I also worked on distributed systems there. Main conclusion, distributed systems
are hard, theoretically and practically. I learn and now fan of the actor model
and the clarity of its variations. I explored and formalised one in
[mailbox-actors](https://github.com/jonaprieto/mailbox-actors), where mailboxes
are promoted to first-class actors, and the same idea specifies node protocols as
[engines](https://specs.anoma.net/main/arch/node/concepts/engine.html), documented
with [a ticker](https://specs.anoma.net/main/arch/node/engines/ticker.html#example-of-a-ticker-engine)
as an example. Another cool idea in the literature is `Tango`, I did a limited version of it
in [elixir-tango](https://github.com/jonaprieto/tango), replicated in-memory
data structures. I also experimented with formal
specifications of a distributed virtual Machine in [AVM Lab](https://anoma.github.io/avm-lab/),
from its instruction set and interpreter semantics to interaction trees and sequential objects.
Interactions trees are quite nice! big fan of this simple but powerful construction.

Back in day, during my master's, I wrote
[online-atps](https://github.com/jonaprieto/online-atps) to run the provers from
[SystemOnTPTP](https://tptp.org/cgi-bin/SystemOnTPTP). I also contributed to
[apia](https://github.com/asr/apia), which
discharges Agda first-order goals with them.
[athena](https://github.com/jonaprieto/athena) turns the
[Metis](https://github.com/gilith/metis) proofs that come
back into checkable Agda terms. It emits into
[agda-prop](https://github.com/jonaprieto/agda-prop) and
[agda-metis](https://github.com/jonaprieto/agda-metis), classical propositional
logic and Metis proof reconstruction in Agda, with
[prop-pack](https://github.com/jonaprieto/prop-pack) as the problem set.

During my PhD, I worked on
[synthetic graph theory](https://jonaprieto.github.io/synthetic-graph-theory/),
graph constructions formalised in HoTT. I co-created
[agda-unimath](https://github.com/UniMath/agda-unimath), a formalization of
univalent mathematics, though I have been mostly absent from it since. If
[HoTT](https://homotopytypetheory.org/)
is your thing and you're learning it, check out my
[hott-cheatsheets](https://github.com/jonaprieto/hott-cheatsheets) and
[mini-hott](https://github.com/jonaprieto/mini-hott). 

I also wrote [agda-pkg](https://github.com/agda/agda-pkg), the `apkg` package
manager for Agda, years ago. It has been unmaintained for nearly as long. I don't
think Agda needs a package manager anymore. 

Before all this, I wrote a lot of Python.
[flask-ponywhoosh](https://github.com/jonaprieto/flask-ponywhoosh) provides
full-text search for [Flask](https://flask.palletsprojects.com/en/stable/) on top of
[ponywhoosh](https://github.com/jonaprieto/ponywhoosh).
</details>

<details>
<summary>A note on AI</summary>

Nowadays, I build with agentic tools at work and have more recently started using
them for my personal projects. A lot of people are against it for several reasons.
To me, AI is another tool in my toolbox.
I continue building as before, but more, and it is hard to keep the same level of supervision.
For the projects I really need, I still write and review every line. But I
don't want to spend all my time and energy reviewing everything I try. Some
of these projects were built with AI, some only in part, some on my own, and some
before any of this. The level of supervision varies. That distinction stopped
mattering to me.

</details>


Notes and talks at [jonaprieto.github.io](https://jonaprieto.github.io/).
