maid_xsection is a MAID sampler for MAID98, MAID2000, and MAID2003.
It needs the JLab build system, so it should be built on the JLab
computer cluster like this:

make && make install

To see usage information, run without any arguments:
maid_xsection

See example/for an example program that links to it.

To use MAID2007, use maid_xsection07.

Example executable usage:

echo '1.5 1.0 0 0' | maid_xsection 2.035 5 2 0 0
