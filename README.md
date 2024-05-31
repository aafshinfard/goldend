Goldend: extract the reads with low repeat content in their ends - the goldend reads
================================================================================

Goldend processes the input long-read dataset, and finds filters reads with high repeat content in their ends (left/right flanks of size --fsize)
Goldend filters a small portion of the read dataset that can complicate downstream analysis, especially when analysing connectivity of reads (e.g read overlap detection, scaffolding, etc).

Instructions
================================================================================
