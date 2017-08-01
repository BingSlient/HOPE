run `embed_main.m` with matlab

Input:

A: N*N adjacency matrix (sparse)

K: dimensionality of embedding space

beta: decaying constant, default is 0.5 / spectral radius

Output:

U: N*K left embedding matrix

V: N*K right embedding matrix

The high-order proximity (katz) matrix is approximated by U * V'
