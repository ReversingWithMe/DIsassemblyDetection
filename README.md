# DIsassemblyDetection

Expiramentation script, not robust, and hasn't been touched in a few years.

Exploring detecting what assembly language a chunk of binary is using Capstone to disassemble and collect valid instruction statistics. Assuming disassembly mode that collects the most valid assembly instructions is the correct one ~100%.

Attempted to play a little with CISC arch shifting byte offsets, and assumes nearly entirely instruction sequence, not much data.

As x86 is close to 95% coverage of bytes, leads to a few issues with approach when large amounts of data.

