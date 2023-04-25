# Parallel Quasi-Monte Carlo Integration by Partitioning Low Discrepancy Sequences

with A. Keller.

In H. Wozniakowski and L. Plaskota (eds.), Monte Carlo and Quasi-Monte Carlo Methods
2010, Springer-Verlag, Berlin, 2012.

*Abstract:* A general concept for parallelizing quasi-Monte Carlo methods
is introduced. By considering the distribution of computing jobs across a multiprocessor
as an additional problem dimension, the straightforward application of quasi-Monte Carlo
methods implies parallelization.  The approach in fact partitions a single
low-discrepancy sequence into multiple low-discrepancy sequences. This allows for
adaptive parallel processing without synchronization, i.e. communication is required
only once for the final reduction of the partial results.  Independent of the number of
processors, the resulting algorithms are deterministic,  and generalize and improve upon
previous approaches.

[Paper](parqmc.pdf)

