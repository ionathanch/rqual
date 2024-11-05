# Research Qualifier – Jonathan Chan – 21 November 2024, 15:30

**Title**: Internalizing Extensions in Lattices of Type Theories \
**Date**: 21 November 2024 \
**Time**: 15:30 \
**Location**: Singh 313 \
**Committee**: [Steve Zdancewic](https://www.cis.upenn.edu/~stevez/) (chair),
  [Stephanie Weirich](https://www.cis.upenn.edu/~sweirich/) (advisor),
  [Benjamin Pierce](https://www.cis.upenn.edu/~bcpierce/)

**Abstract**: \
While many proof assistants are founded upon common theoretical ground,
they will also feature further extensions and axioms that augment their reasoning power.
The individual theories based on each extension are individually sound,
but how type checkers handle their interactions at compile time is not formally described.
Furthermore, the way proof assistants currently enable extensions can be too coarse and imprecise
when it comes to guarantees about the features a top-level definition may use.

A first step towards a framework of extensions could use
the Dependent Calculus of Indistinguishability (DCOI)
to formalize granular and precise extension tracking.
DCOI is a type system with dependency tracking,
where terms and variables are assigned dependency levels alongside their types.
These dependency levels form a lattice that describes which levels are permitted to access what.
This report explores how extensions could correspond to dependency levels,
and how the lattice would describe how extensions are permitted to interact.
