LFSR
==

This repository is comprised of 2 sudmodules, matlab_lfsr and verilog_lfsr. 

[Wikiepedia LFSR](http://en.wikipedia.org/wiki/Linear_feedback_shift_register)

Fibonacci LFSRs are implemented as shift register with taps to a multibit xor to create a feedback value. The feedback is into position 1 and are n bits long. If using a maximal length LFSR the sequence will be 2^n - 1 bits long before repeating.

Galois LFSRs are implemented as a shift register, the feedback is direct and taps XOR the bit with the current output to generate the next bit. The feedback is from bit 1 to bit 16, the opposite of the Fibonacci LFSR.

For the best performance of an LFSR it should be of maximal length. Maximal length asserts for the given shift register length and number of taps you have the longest random number sequence possible. A list of taps can be found on [Philip Koopmans LFSR Page](http://www.ece.cmu.edu/~koopman/lfsr/index.html).


