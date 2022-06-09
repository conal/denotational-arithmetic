## Arithmetic via denotational design

This repository is an experiment in teaching and collaborating on denotational design.

The Agda standard library defines arithmetic for `ℕ` in `Data.Nat`, particularly `0`, `1`, `_+_`, and `_*_`.
The puzzle to be addressed in this project is elegant specification and correct calculation of these same operations on a *binary* representation.
The specifications should be homomorphic, centered on a denotation `⟦_⟧ : Vec Bool n → ℕ`.

Please read and contribute to the project [discussions](https://github.com/conal/denotational-arithmetic/discussions).
