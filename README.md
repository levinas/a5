A5
==

This is a forked version of the A5 Assembly Pipeline hosted at 

http://code.google.com/p/ngopt/

(Tritt, Andrew, et al. "An integrated pipeline for de novo assembly of microbial genomes." PloS one 7.9 (2012): e42304.)

Please see A5PipelineREADME for copyright and license information.


Modifications
-------------

1. Fixed a bug in detecting Phred64 quality coding.
2. Added the latest idba_ud for iterative assembly.
3. Fixed idba_ud's support for longer reads (up to 256bp).

The new script bin/a5 replaces the original script bin/a5_pipeline.pl.
