# gtp-uppaal
A formal verification of the gossip protocol GTP using the model checker Uppaal.

`gtp.xml` is the Uppaal file containing the timed automata describing processes in GTP. Configure Uppaal with the following options, in order to reproduce the reported model checking results:

* Search order: depth first
* State space reduction: conservative
* State space representation: DBM
* Diagnostic trace: some
* Extrapolation: automatic
* Hash table size: 16MB
* Reuse: yes
* Parametric comparisons: yes
* Modest: no

## Requirements

* Uppaal 4.1.19 : http://www.uppaal.org/
