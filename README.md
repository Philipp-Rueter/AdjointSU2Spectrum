# AdjointSU2Spectrum

This program provides an algorithm to compute the BPS spectrum of the N=2* SU(2) theory, also known as the adjoint SU(2) theory, as it contains a hypermultiplet in the adjoint representation. The algorithm is built on the analysis of Longhi in his thesis "The Structure of BPS Spectra", which gives the spectrum on a wall of marginal stability, where one of the base charges aligns with the flavor charge. Starting from that spectrum, the algorithm does a step by step perturbation away from that wall and computes the new spectrum using the Kontsevich-Soibelman wall crossing formula.

The first part of the program consists of defining classes and functions to handle the BPS states and their permutations. This leads to the definition of the main function which computes the spectrum on the basis of various parameters. The main sections relevant for users are "Parameters and Options" as well as "Resulting Spectrum and Diagnostics".

Finally we have two sections to write the data into a JSON file and to plot it.

This program has been used to compute parts of the spectrum for a paper which is joint work with Richard Szabo. We also include the data of the computations of that paper in a seperate folder. This data is again packaged in JSON files and can be read with the main program.
