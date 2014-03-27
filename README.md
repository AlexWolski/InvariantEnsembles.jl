InvariantEnsembles.jl
=====================

Sample random unitary invariant ensembles


# Sample n x n quartic ensemble w(x) = exp(-n x^4) eigenvalues, m times
samplespectra("Quartic",n,m)

# Sample n x n quartic ensemble w(x) = exp(-x^8) eigenvalues, m times
samplespectra("EightUnscaled",n,m)

# Sample n x n cosh ensemble w(x) = exp(-cosh(x)) eigenvalues, m times
samplespectra("CoshUnscaled",n,m)

# Sample n x n high order decay ensemble w(x) = exp(-(x.^4/20 -4/15*x.^3 + x.^2/5+8/5*x)) eigenvalues, m times
samplespectra("HODecay",n,m)

