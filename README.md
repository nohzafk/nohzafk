# nohz.afk

I learn by building. My interests move across programming languages, developer
tools, human–agent systems, and experiments that turn an idea into something I
can test. I write about what I learn by building, measuring, and using things in
practice.

[Blog](https://nohzafk.github.io/) ·
[Bend 2, from zero](https://nohzafk.github.io/bend2-from-zero/)

## What I build with

**Gleam.** I learned Gleam by porting
[The Little Learner](https://github.com/nohzafk/the_gleam_learner), a book that
builds deep learning from first principles, into it. Along the way I wrote a
parser-combinator [JSON parser](https://github.com/nohzafk/gjson-parser) and
[gtransducer](https://hex.pm/packages/gtransducer), a library on Hex that fuses
mapping, filtering and reducing into one pass over the data, and can reduce in
parallel.

**Emacs.** Emacs is where I work all day, so many of my tools live there.
[emacs-egui](https://github.com/nohzafk/emacs-egui) lets Emacs host GPU-drawn
Rust/egui apps compiled to WebAssembly;
[emacs-workspace-hud](https://github.com/nohzafk/emacs-workspace-hud) is one of
them, a floating card with Git, LSP and diagnostic state.
[consult-snapfile](https://github.com/nohzafk/consult-snapfile) finds files
instantly through a Rust backend, [cli2eli](https://github.com/nohzafk/cli2eli)
turns any command-line tool into Emacs commands, and
[emacs-anywhere](https://github.com/nohzafk/emacs-anywhere) lets me edit text
from any macOS app in Emacs.

**Bend.** Bend 2 lets you state a law about a function and prove it for every
input. I learned it by writing
[Bend 2, from zero](https://github.com/nohzafk/bend2-from-zero), a book built
from runnable experiments: affine values, parallel CPU and GPU execution,
Conway’s Life, laws and proofs, with a measurement behind every performance
claim. Then I put the proofs to work.
[bend-emit](https://github.com/nohzafk/bend-emit) compiles a pure Bend core into
a typed ES module, so TypeScript imports the very functions the proofs are
about. [bend-schema](https://github.com/nohzafk/bend-schema) is built on it: a
JSON schema library whose checker is proved correct, not only tested.

**Elle.** For Elle, a Lisp written in Rust, I built
[tree-sitter-elle](https://github.com/nohzafk/tree-sitter-elle), a grammar that
makes structural search and rewriting with ast-grep possible.

## Working with agents and machines

- **Tools for working with agents** —
  [memhub](https://github.com/nohzafk/memhub) shares long-term memory across
  machines and coding agents; [ClaudePad](https://github.com/nohzafk/claude-pad)
  and [agent-shell-hud](https://github.com/nohzafk/agent-shell-hud) explore ways
  to direct and observe agents without losing your own train of thought.
- **Systems in the real world** — I document the details that usually disappear,
  from making [Linux work on a T1 MacBook Pro](https://github.com/nohzafk/omarchy-macbookpro-t1)
  to building a multi-channel [writing and publishing system](https://nohzafk.github.io/).

## Open-source contributions

- **[Elle](https://github.com/elle-lisp/elle)** — my
  [merged contributions](https://github.com/elle-lisp/elle/pulls?q=is%3Apr+is%3Amerged+author%3Anohzafk)
  span compiler correctness, region-inference performance, standard-library
  caching, stack safety, cross-thread ownership, and macOS support.
- **[Bend](https://github.com/bendlang/bend)** — the
  [issues I filed](https://github.com/bendlang/bend/issues?q=is%3Aissue+author%3Anohzafk)
  found bugs in the compiler and its diagnostics, the law and proof system, package
  resolution, and the macOS runtime; several are fixed upstream.
- **[lsp-bridge](https://github.com/manateelazycat/lsp-bridge)** — a fast LSP
  client for Emacs. I built its Dev Container integration and
  [contributed language-server support and concurrency fixes](https://github.com/manateelazycat/lsp-bridge/pulls?q=is%3Apr+is%3Amerged+author%3Anohzafk).

## GitHub activity

<!-- Generated weekly by lowlighter/metrics. -->
<picture>
  <img src="/github-metrics.svg" alt="GitHub language activity" width="480">
</picture>
