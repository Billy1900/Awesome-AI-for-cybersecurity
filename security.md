# 1. Control/Data Flow Analysis (CFG/DFG)
A data-flow graph (DFG) is a graph which represents a data dependency between a number of operations. A control-flow graph (CFG) is a directed graph where the nodes are basic blocks (a section of code with a single entry and a single exit point) and edges represent branch/jump instructions.

## DFG generation Tool
This is a simple [example](http://bears.ece.ucsb.edu/research-info/DP/dfg.html) of DFG, and more detailed [Introduction.](http://pages.cs.wisc.edu/~horwitz/CS704-NOTES/2.DATAFLOW.html)

- [Perf tools](https://perf.wiki.kernel.org/index.php/Perf_tools_support_for_Intel%C2%AE_Processor_Trace) are packaged based on the kernel version, which means the version of perf provided by Linux distributions is always quite old, whereas updates to Intel PT support are happening all the time. That means, for the latest Intel PT features, we really need to download and build that latest perf.

- [angr](https://angr.io/) is a python framework for analyzing binaries. It combines both static and dynamic symbolic ("concolic") analysis, making it applicable to a variety of tasks.

- [PolyTracker](https://github.com/trailofbits/polytracker) is a tool originally created for the Automated Lexical Annotation and Navigation of Parsers, a backronym devised solely for the purpose of referring to it as The ALAN Parsers Project. 

# 2. Dynamical analysis
This repository lists [dynamic analysis tools](https://github.com/analysis-tools-dev/dynamic-analysis) for all programming languages, build tools, config files and more.

# Misc
- [CTF-wiki](https://ctf-wiki.org/): CTF Wiki mainly contains the basic skills for CTF.
- [CTF tools](https://ctf-wiki.github.io/ctf-tools/): collections of tools used in CTF.
- [CTF All in One](https://firmianay.gitbooks.io/ctf-all-in-one/content/): CTF contest introduction
