# Installation

[ngspice](https://ngspice.sourceforge.io/index.html)

[ngspice for vlsi - Claudio Talarico](https://web02.gonzaga.edu/faculty/talarico/vlsi/ngspice.html)


# Content

1. [Attenuator](attenuator/readme.md)


# ngspice command

### To work on the circuit 

*ngspice filename.cir*

### To view the netlist of circuit 
*listing*

### To excute Op (Operating Point Analysis) 
*op* 

### To see Voltage or Current at Point or Node

*print v(a)*

### To run use control command

```
.control
op
print v(a) v(b) v(a,b) i(v1)
.endc
```

### To update the changes in circuit

*source filename.cir*
