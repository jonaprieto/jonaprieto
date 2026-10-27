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

Things I built for myself:

- [PaperShelf](https://github.com/jonaprieto/papershelf), the PDF reader and library manager I wish I'd had years ago.
- [folio](https://github.com/jonaprieto/folio), finds and downloads a book or paper from the terminal.
- [tess](https://github.com/jonaprieto/tess), a keyboard-first tiling window manager.
- [EdgeMark](https://github.com/jonaprieto/EdgeMark), my fork of [Ender-Wang's](https://github.com/Ender-Wang/EdgeMark) side-panel notes app, synced to GitHub.
- [nuphy-air96](https://github.com/jonaprieto/nuphy-air96), the keymap and a menu bar app for my NuPhy Air96 keyboard.
- [zkit](https://github.com/jonaprieto/zkit), a numbered `ls`, so `rm 3` removes what I just saw.
- Sombra, an Android TV app for my TV: it plays from Stremio addons and turns subtitles into language practice (private repo).


<details>
<summary>In the works</summary>

[OATP](https://github.com/jonaprieto/oatp), a Lean 4 REPL and CLI for automated
theorem provers. It parses [TPTP](https://tptp.org) and runs local and online
provers. It started as my Haskell [online-atps](https://github.com/jonaprieto/online-atps).

What I wrote for it along the way:

- [Grip](https://github.com/jonaprieto/lean-grip), a graded parser-combinator library, inspired by [prim-parser](https://github.com/janmasrovira/prim-parser). Recursive parsers terminate without `partial`.
- [grip-tptp](https://github.com/jonaprieto/lean-grip-tptp), TPTP on Grip.
- [grip-json](https://github.com/jonaprieto/lean-grip-json), JSON on Grip.
- [grip-diagnostics](https://github.com/jonaprieto/lean-grip-diagnostics), readable parse errors.
- [Argus](https://github.com/jonaprieto/lean-argus), typed command-line parsing; help and shell completions come from one spec.
- [termcolor](https://github.com/jonaprieto/lean-termcolor), ANSI colours and styled text, with [layout](https://github.com/jonaprieto/lean-termcolor-layout), [diagnostics](https://github.com/jonaprieto/lean-termcolor-diagnostics), [widgets](https://github.com/jonaprieto/lean-termcolor-widgets), [terminal](https://github.com/jonaprieto/lean-termcolor-terminal) and [repl](https://github.com/jonaprieto/lean-termcolor-repl).
- [calc-chat](https://github.com/jonaprieto/lean-calc-chat), a chat-shaped terminal calculator, to try termcolor.
- [precommit-lean](https://github.com/jonaprieto/precommit-lean), hooks for Lean style, module names and allowed axioms, plus the [/lean-format](https://github.com/jonaprieto/precommit-lean/blob/main/.claude/commands/lean-format.md) command.

</details>

<details>
<summary>More (old) projects: Juvix, distributed systems, Agda and HoTT</summary>

I used to think [Haskell](https://www.haskell.org/) would become the next big language for me at least.
Now I think it is any theorem prover with general-purpose programming support and dependent
types. That is Lean 4, it could have been Agda, but AI simply pushed Lean so much, made it mainstream, that
it would be a mistake to not learn it, and it's really fun, actually! I still miss Agda-way of proving things,
  proof-term construction I mean.

At [Heliax](https://heliax.dev/), on the [Juvix](https://github.com/anoma/juvix) language, where I was one of the main contributors:

- [juvix-docs](https://github.com/anoma/juvix-docs), [vscode-juvix](https://github.com/anoma/vscode-juvix), [juvix-stdlib](https://github.com/anoma/juvix-stdlib) and [juvix-mode](https://github.com/anoma/juvix-mode), which I maintained.
- [juvix-mkdocs](https://github.com/anoma/juvix-mkdocs), literate docs, used for the [Juvix tutorial](https://docs.juvix.org/latest/tutorials/learn.html#data-types-and-functions).

Distributed systems, also at Heliax:

- [mailbox-actors](https://github.com/jonaprieto/mailbox-actors), an actor model where mailboxes are actors too.
- [Engines](https://specs.anoma.net/main/arch/node/concepts/engine.html), the same idea for Anoma's node protocols, with [a ticker](https://specs.anoma.net/main/arch/node/engines/ticker.html#example-of-a-ticker-engine) as the example.
- [elixir-tango](https://github.com/jonaprieto/tango), a small Tango: replicated in-memory data structures.
- [AVM Lab](https://anoma.github.io/avm-lab/), a formal spec of a distributed virtual machine, down to interaction trees.

From my master's:

- [online-atps](https://github.com/jonaprieto/online-atps), runs the provers on [SystemOnTPTP](https://tptp.org/cgi-bin/SystemOnTPTP).
- [apia](https://github.com/asr/apia), which I contributed to, proves Agda first-order goals with them.
- [athena](https://github.com/jonaprieto/athena), turns [Metis](https://github.com/gilith/metis) proofs into Agda terms.
- [agda-prop](https://github.com/jonaprieto/agda-prop) and [agda-metis](https://github.com/jonaprieto/agda-metis), propositional logic and Metis proofs in Agda, tested on [prop-pack](https://github.com/jonaprieto/prop-pack).

From my PhD:

- [Synthetic graph theory](https://jonaprieto.github.io/synthetic-graph-theory/), graphs in HoTT.
- [agda-unimath](https://github.com/UniMath/agda-unimath), univalent mathematics in Agda. I co-created it, but have been mostly away since.
- [hott-cheatsheets](https://github.com/jonaprieto/hott-cheatsheets) and [mini-hott](https://github.com/jonaprieto/mini-hott), if you are learning [HoTT](https://homotopytypetheory.org/).

Older still:

- [agda-pkg](https://github.com/agda/agda-pkg), `apkg`, a package manager for Agda. Unmaintained; I don't think Agda needs one anymore.
- [flask-ponywhoosh](https://github.com/jonaprieto/flask-ponywhoosh), full-text search for [Flask](https://flask.palletsprojects.com/en/stable/), on [ponywhoosh](https://github.com/jonaprieto/ponywhoosh).

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
