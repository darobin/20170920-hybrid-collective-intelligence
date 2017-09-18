

### Novel thermodynamic properties of computational processes (David Wolpert and Artemy Kolchinsky)

5% of US expenditure.
Allowing noise in computation reduces energy requirements. Increase errors at the chip level,
basically transfer noise from the environment into the processing.

"Intelligence is extremely costly. Evolution will try to keep people stupid. There is a big
evolutionary advantage to being Donald Trump."

The biosphere's computational efficiency is orders of magnitude better than the best computer.

Dissipation depends on the mismatch between the assumed priors in the computational design and the
actual requirements of the tasks being carried out.

There is a thermodynamic version of Kolmogorov complexity, which is that you replace the minimal
size of a string that produces a given output with the minimal *work* required to produce that
same bitstring. Minimal work is bounded even though Kolmogorov complexity is not (the expected work
is infinite).

Lots of work to be done on "thermodynamicising" computer science, see for instance if you get the
same complexity classes and the such.

  * => Check out circuit design theory, has interesting implications with complex problems. Might
    have interesting implications for communication over graphs. Random graphs creating circuits
    with varying properties, notably in the difference between expectations and actual distribution
    of events.
    - I wonder if this could be in any way related to expectations in Bayesian systems, and how to
      bridge them to QI and imaginary amplitudes
    - check out "information reservoirs". Do they produce waves by "emptying" regularly (possibly
      at criticality)

### Thermodynamics of Requisite Complexity (Alec Boyd)

Ordered/predictable environments are a thermal source (they can be used to produce work).
Thermodynamically efficient agents must match the XXX of their environment to work.

Thermodynamics of intelligent systems (=demons)
Thermal reservoir vs information reservoir? Yes! If you dump your information into an information
reservoir instead of erasing it to keep processing (cf Landauer, Maxwell's Demon) then you do not
lose work but you increase entropy.

  * => check out the thermodynamics of modularity, it came up a few times


### Topological analysis of multicellular complexity in the plant hypocotyl (George Bassel)

Cells do not migrate, they are stuck together. Plants are supercellular, all cells communicate with
their neighbours.
Plant cells are stem cells, they are specialised based on their location.
Mapping structural cellular networks (with fluorescence): basically the global cellular equivalent
to connectome studies. Then turn this into a network at single-cell resolution.
Based on this, discretise multicellular organisation into connectivity networks.

### The role of multiple feedback circuits in the regulation of the size and number of attractors in Boolean networks (Eugenio Azpeitia, Stalin Muñoz, Daniel Gonzalez-Tokman, Mariana Esther Martinez-Sanchez, Nathan Weinstein, Aurelien Naldi, Elena Alvarez-Buylla, David A. Rosenblueth, and Luis Mendoza)

There is a maximum number of (fixed-point) attractors in a Boolean network that depends on how you
cut it up (see picture). This seems very much related to Judea Pearl's causal graphs.

  * => Check out "Griffin", tool that can do Boolean Network analysis, highly efficient.

Number of positive circuits is correlated to number of attractors; number of negative circuits is
correlated to the size of attractors. (positive/negative = excitatory/inhibitory).

  * Can a similar excitatory/inhibitory mapping be made in Q cases (for specific observables, since
    they are transformations, and therefore could be seen in the same way)? This could lead to
    "reality attractors" as states become entangled in complex ways (this assumes entanglement has
    some transitive-like features that enables the building of networks).

### Conserved homological cores of structural and functional brain networks across age ()

To what degree is the brain a topological machine? Mathematical topology, not statistical topology.

In simplicial constructs you know more than with networks because you know if eg a triangle is full
or not (in the latter case, it's just the addition of three edges = 1-simplicial).

So with ball/neighbourhood analysis you can see which balls overlap, and given n-overlaps you get
a network of n-simplicials.

In doing simplicial approximations, you iterate through all sizes of balls, and measure the number
of n-simplicials that you get at each coarse-graining. This allows you to detect topological
features. These can be used as features for machine learning. It can give a sense of which
coarse-graining makes sense.

Based on the weights and barcodes, you get a homological scaffold.

  * => check out more on this, it went too fast.

The brain, from a homological point of view, ages like a drying sponge.

Functional preservation through topological presentation. (hypothesis)
