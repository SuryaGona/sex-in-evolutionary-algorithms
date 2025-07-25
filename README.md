Sex as an Algorithm: The Theory of Evolution Under the Lens of Computation

Contributors: Wyatt Miller, Surya Harshith Gona, Levi Nzapo Sumbela
Instructor: Prof. Panagopoulos
Course: CSCI 165
Date: April 23, 2025

🧬 Overview

This project explores "Sex as an Algorithm," the 2016 paper by Adi Livnat and Christos Papadimitriou, which applies computational theory to deepen our understanding of sexual reproduction and evolution. Specifically, the authors investigate why a process that appears algorithmically inefficient — sexual recombination — has proven so dominant in nature.

Using insights from computer science, evolutionary biology, and game theory, the authors argue that sexual evolution does not aim to preserve the "best" individuals but rather optimizes for population-level robustness by selecting mixable alleles.

🧠 Key Concepts

Genetic Algorithms vs. Nature
Asexual reproduction in optimization problems outperforms sexual methods due to preservation of top solutions.
Sexual reproduction, however, introduces recombination — leading to a loss of even optimal genotypes.
This inefficiency is overcome by nature through mixability: alleles that perform well across varied combinations are favored.
Evolution as a Coordination Game
The authors propose that evolution resembles a coordination game, with genes acting as players adjusting their strategies.
Evolution uses a multiplicative weights update algorithm to assign probabilities to alleles based on their mixability.
Efficiency Through Randomization
In sexual evolution, it takes only log(n) generations to test all genetic combinations of an allele — an exponential efficiency gain.
This enables population-wide exploration of genetic space in a way deterministic algorithms struggle with.
Non-Random Mutation
Later work by Livnat and collaborators shows that mutations may be adaptive and context-sensitive, not purely random.
For instance, a malaria-resistant gene mutation appeared more frequently where it was beneficial, offering evidence for targeted evolution.
📖 Reflection

“Presenting this article was challenging due to its technical depth. My original approach aimed to cover as much as possible using a script, but it led to a dry, non-interactive delivery. If I were to do it again, I'd narrow the focus and emphasize key ideas in a more dynamic format.”
— Wyatt Miller
🧾 Works Cited

Livnat, A. & Papadimitriou, C. (2016). Sex as an Algorithm: The Theory of Evolution Under the Lens of Computation. Communications of the ACM, 59(11), 84–93.
Vasylenko, L., Feldman, M. W., Papadimitriou, C., & Livnat, A. (2019). Sex: The Power of Randomization. Theoretical Population Biology, 129, 41–53.
Vasylenko, L., Feldman, M. W., & Livnat, A. (2020). The Power of Randomization by Sex in Multilocus Genetic Evolution. Biology Direct, 15(26).
Melamed, D., Nov, Y., Malik, A., & Livnat, A. (2022). De novo Mutation Rates at the Single-Mutation Resolution in a Human HBB Gene Region. Genome Research, 32(3), 488–498.
