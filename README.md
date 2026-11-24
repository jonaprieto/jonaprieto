Hello there! I use this account for personal projects but also for work. 
I like building things from math projects to everyday software.

At work, I'm a core developer of [Anoma](https://anoma.net/) at [Heliax](https://heliax.dev/),
working remotely on my own schedule. I have worked across most of it, from the
[Juvix](https://github.com/anoma/juvix) language, [formal specs](https://specs.anoma.net/)
of the protocol and [research reports](https://art.anoma.net/) to the
[smart contracts](https://github.com/anoma/pa-evm), and the
[indexers](https://github.com/anoma/anoma-envio) and
[explorers](https://github.com/anoma/anoma-explorer) on top. I'm also an internal
reviewer, of the [Resource Machine](https://github.com/anoma/arm-risc0) implementation
and the Solidity contracts among others. That has meant using whatever the job needed,
from Haskell, Agda and Lean to Elixir, TypeScript, Rust and Solidity.

In my spare time, I'm learning [Lean](https://lean-lang.org/) and using
[Agda](https://agda.readthedocs.io/) for my HoTT constructions.
For AI-driven web apps, I use Elixir and [Phoenix](https://www.phoenixframework.org/).
Phoenix is a big reason I switched from Python to Elixir for building apps.

My Mac, mostly rebuilt to my taste:

- [Ghostty](https://github.com/jonaprieto/ghostty), my fork of [Ghostty](https://github.com/ghostty-org/ghostty), as a dropdown terminal with tabs, a menu bar icon and tmux in every tab. Clicked folders open in a split, source files in Zed.
- [Zed](https://zed.dev/) is my editor. I work on [zed-lean4-ide](https://github.com/jonaprieto/zed-lean4-ide), my fork of [reuixiy7's](https://github.com/reuixiy7/zed-lean4) Lean 4 extension, with an infoview in a terminal beside the code, and on [zed-wkey](https://github.com/jonaprieto/zed-wkey), a which-key for Zed's vim mode.
- [Strata](https://github.com/jonaprieto/strata-files), my fork of [cristipufu's](https://github.com/cristipufu/strata-files) file manager, which replaces Finder for me. I added Magit-style git with a commit graph, a history panel, a terminal drawer and Dired keys.
- [Tesela](https://github.com/jonaprieto/tesela), a keyboard-first tiling window manager that replaces Alfred, Magnet and Spotlight for me, among others. A letter on every window, and one fuzzy picker for windows, tabs, apps and files.
- [PureMac](https://github.com/jonaprieto/PureMac), my fork of [momenbasel's](https://github.com/momenbasel/PureMac) Mac cleaner, with Free Up and Clean in the menu bar and Move to Trash in Space Explorer.
- [EdgeMark](https://github.com/jonaprieto/EdgeMark), my fork of [Ender-Wang's](https://github.com/Ender-Wang/EdgeMark) side-panel notes app, synced to GitHub.
- [zkit](https://github.com/jonaprieto/zkit), a numbered `ls`, so `rm 3` removes what I just saw.
- [folio](https://github.com/jonaprieto/folio), finds and downloads a book or paper from the terminal.

Other things I built for myself:

- [PaperShelf](https://github.com/jonaprieto/papershelf), the PDF reader and library manager I wish I'd had years ago.
- [nuphy-air96](https://github.com/jonaprieto/nuphy-air96), the keymap and a menu bar app for my NuPhy Air96 keyboard.
- [Sombra](https://jonaprieto.github.io/sombra/), an Android TV app for language learners: it plays from Stremio addons and turns the subtitles into practice.


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

I build with agentic tools at work, and more recently for my personal projects
too. Many people are against it, for several reasons. To me, AI is one more tool.
I build as before, only more, and that makes it hard to supervise everything the
same way. For the projects I really need, I review the core parts of the code
myself and leave the non-essential parts to AI auditing. I don't want to spend all
my time and energy reviewing everything I try. Some of these projects were built
with AI, some only in part, some by me alone, and some before any of this, so how
closely I supervised each one varies.

</details>


Notes and talks at [jonaprieto.github.io](https://jonaprieto.github.io/).
