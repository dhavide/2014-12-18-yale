Instructions for protein_sequence_data.csv

This file contains a multiple sequence alignment for approximately 1000 protein sequences. Each row is a protein sequence with its amino acids separated by commas using single letter abbreviations for amino acids. For ease of analysis, all proteins are exactly the same length (i.e., no alignment gaps).

Goals:
1. Calculate the frequency of each amino acid at each alignment position. This can be accomplished in many ways, but for practice, try to think of the data as a matrix and use matrix operators whenever possible.

2. Visualize the frequency data in any format (hint: the bioinformatics toolbox can be helpful here).

Instructions for binding_data.csv

This file contains data for three protein-protein interactions. For simplicity, there are three different variants of protein #1 (called A, B, and C) that interact with protein #2. For each interaction, there are two rows of accompanying data. The first row contains the amount of protein #1 added to each tube (which already contained a trace quantity of the interacting protein #2). The second row contains the apparent fraction of protein #2 bound at the given concentration of protein #1. This data can be fit to the following model:
y = x/(K+x),
where x is the concentration of protein #1 added, y is the fraction of protein #2 bound at that concentration of protein #1, and K is a constant that describes the affinity of the interaction between proteins #1 and #2.

Goal:
Determine K for each of the three variants (A, B, and C) of protein #1. For those with a keen knowledge of equilibrium binding, you know how to estimate the answers directly from the data. But don't cheat! That's not the point of the exercise. Only use your knowledge to double-check your answers from data fitting :-)
