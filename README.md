# Formalizing Mathematics in Lean 4

This repository contains the materials for the course **"Formalizing Mathematics in Lean"**, taught as part of the [**Sixth EACA International School on Computer Algebra and its Applications**](https://www.usc.es/regaca/eacaschool23/index.html) (Santiago de Compostela, July 18 - 21, 2023).

## Tutorials and Exercises
For each of the sessions, I will present a tutorial and then give you some exercises to solve. Some of the sessions will also include a tactic guide. All of the files can be tested online without installing Lean locally.

For each exercise session, click on the corresponding link below. You might have to wait for a minute or so until the server starts and the orange bars go away. Then, you can go ahead and replace each sorry by a valid proof.

Session 1: Logic.
The [Tutorial](https://lean.math.hhu.de/#url=https%3A%2F%2Fraw.githubusercontent.com%2Fmariainesdff%2FEACA_School%2Fmaster%2F1_logic%2Flogic_tutorial.lean), the [Exercises](https://lean.math.hhu.de/#url=https%3A%2F%2Fraw.githubusercontent.com%2Fmariainesdff%2FEACA_School%2Fmaster%2F1_logic%2Flogic_exercises.lean), and the [Tactic Guide](https://lean.math.hhu.de/#url=https%3A%2F%2Fraw.githubusercontent.com%2Fmariainesdff%2FEACA_School%2Fmaster%2F1_logic%2Ftactics.lean).

The slides from the first session are available [here](https://github.com/mariainesdff/EACA_School/blob/master/1_logic/session_1.pdf).

Session 2: Functions.
The [Tutorial](https://lean.math.hhu.de/#url=https%3A%2F%2Fraw.githubusercontent.com%2Fmariainesdff%2FEACA_School%2Fmaster%2F2_functions%2Ffunctions_tutorial.lean), the [Exercises](https://lean.math.hhu.de/#url=https%3A%2F%2Fraw.githubusercontent.com%2Fmariainesdff%2FEACA_School%2Fmaster%2F2_functions%2Ffunctions_exercises.lean), and the [Tactic Guide](https://lean.math.hhu.de/#url=https%3A%2F%2Fraw.githubusercontent.com%2Fmariainesdff%2FEACA_School%2Fmaster%2F2_functions%2Ftactics_2.lean).

Session 3: Structures and classes.
We will discuss [Structures](https://lean.math.hhu.de/#url=https%3A%2F%2Fraw.githubusercontent.com%2Fmariainesdff%2FEACA_School%2Fmaster%2F3_structures%2Fstructures.lean), [Classes](https://lean.math.hhu.de/#url=https%3A%2F%2Fraw.githubusercontent.com%2Fmariainesdff%2FEACA_School%2Fmaster%2F3_structures%2Fclasses.lean), and examples from [Group Theory](https://lean.math.hhu.de/#url=https%3A%2F%2Fraw.githubusercontent.com%2Fmariainesdff%2FEACA_School%2Fmaster%2F3_structures%2Fgroups.lean). See also the [Tactic Guide](https://lean.math.hhu.de/#url=https%3A%2F%2Fraw.githubusercontent.com%2Fmariainesdff%2FEACA_School%2Fmaster%2F3_structures%2Ftactics_3.lean).

## Installation Instructions
Lean 4 installation instructions can be found [here](https://leanprover-community.github.io/get_started.html).

If you have Lean 4 installed in your computer and you prefer to work with a local copy of this repository, first clone the repository using
```
git clone https://github.com/mariainesdff/EACA_School
```

Then navigate to the `EACA_School` directory and run `lake update` and `lake exe cache get` to get an updated version of the Mathlib cache.

Type `code .` to open the folder in `VS Code`.

## Other resources

1. [The Natural Number Game](https://adam.math.hhu.de/\#/g/hhu-adam/NNG4)
2. [Mathematics in Lean](https://leanprover-community.github.io/mathematics_in_lean/)
3. [MSRI Summer School on Formalization of Mathematics](https://www.msri.org/summer_schools/1021)
4. [Theorem Proving in Lean 4](https://leanprover.github.io/theorem_proving_in_lean4/)
5. [Lean community webpage](https://leanprover-community.github.io/)
6. [Lean Zulip chat](https://leanprover.zulipchat.com/)

Copyright (C) 2023, María Inés de Frutos-Fernández
