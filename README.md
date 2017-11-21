# CS3650Challenge02
I'm finally getting around to posting these here.

This is a parallelized memory allocator, called hmalloc.  It runs faster than the default system allocator.  Personally, I wouldn't recommend using it, though, since it doesn't have any coalescing, so it will eventually fill the entire memory.  Exercise caution.
