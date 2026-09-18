# Huffman-Distances

This repository accompanies the letter "On the Distance Properties of Huffman Sequences" [1], which studies the pairwise distances between Huffman sequences (and sequences with a fixed aperiodic autocorrelation more generally).

The repository includes the following:
  1) Detailed proofs of Proposition 4 and Proposition 5 (see `proof_proposition_4.pdf` and `proof_proposition_5.pdf`).
  2) A summary of properties of the polynomial from Conjecture 1:
     
       $$
       p_K(z)=z^{2K}-z^{2K-1}-4z^K-z+1, \quad K\geq2.
       $$

     This polynomial exhibits similar properties to the Gonchar polynomials [2] (see `properties_of_p(z).pdf`).
     
 ---
     
<p align="center">
  <img src="animations/huffman_distances_K2.gif" alt="Animation">
</p>

<p align="center">
  <b>Figure 1.</b> Pairwise distances between real-valued Huffman sequences of length $K+1=3$ as a function of $R>1$.
</p>

## References
[1] P. Huggins, A. Şahin, and E. Erkip, "On the distance properties of Huffman sequences," *IEEE Commun. Lett.*, in preparation.

[2] J. Brauchart, P. Dragnev, E. Saff, and C. van de Woestijne, "A fascinating polynomial sequence arising from an electrostatics problem on the sphere," *Acta Math. Hungar.*, vol. 137, no. 1-2, pp. 10-26, Mar. 2012.

