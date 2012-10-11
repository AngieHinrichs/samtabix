samtabix
========

This is a merge of AngieHinrichs/samtools (lh3/samtools patched to allow alternate network lib and not check EOF) and tabix-0.2.6 downloaded from samtools.sourceforge.net.  I replaced samtools' bgzf.[ch] with tabix's because tabix's seemed more recent. Had to modify some samtools files to work with updated bgzf.h.