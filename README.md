# Square-Filling Motifs

**https://guillochon.github.io/square-filling-motifs/**

Hilbert-style square-filling curve motifs, after Douglas M. McKenna,
[Fibbinary zippers in a monoid of toroidal Hamiltonian cycles that generate Hilbert-style square-filling curves](https://doi.org/10.54550/ECA2022V2S2R13),
Enumerative Combinatorics and Applications 2:2 (2022). A motif is a path along tile edges through an n×n grid,
one edge per tile. Replacing every tile by a turned copy of the motif, again and again, gives a square-filling curve;
the motifs whose iterates never touch themselves are counted by OEIS [A350148](https://oeis.org/A350148).

- **Viewer.** Pick a grid size (5×5 to 13×13), a zipping mode and a motif, and see G, G², G³, … coloured along the
  curve or by side of the path (McKenna's inside/outside colouring), with the path traced on request.
- **Gallery.** Every motif up to 9×9 (1, 7 and 10,101 of them); uniform random samples for 11×11 and 13×13.
- **Torus.** The motif with its eight neighbours, showing the single loop on the torus and the frozen outer ring
  with its zipper bits.
- **Counts.** a(n) per zipping mode, including the new terms for 13×13, 15×15 and 17×17.

The motifs and counts come from a frontier transfer matrix (code, logs and checks:
[oeis-results/A350148](https://github.com/guillochon/oeis-results/tree/main/A350148)); every motif shown passed an
exact test that its iterates never self-contact. One HTML file plus `motifs.js` (the motif data); no build step.

Made by James Guillochon with Claude.
