Definitions
-----------

This repository contains a collection of elos definitions. Definitions can be thought of as configuration, and there should be some sort of separation -- if at all possible -- between configuration and code. 

I think separately about the space of configuration -- of domain logic -- and the space of application code, of the systems that enable that domain logic to exist. I think these two spaces should be distinct, to allow flexibility in implementation, but that there does exist an isomorphic transformation between them.

These definitions attempt to be the kernel of this abstracted structure, the alpha and omega of the elos ontology, the alpha and omega of the topology of the elos api. We can make use of code generation to create specific implementations based on these well-defined bases.
