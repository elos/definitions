definitions
-----------

This repository holds a collection of elos definitions. There is a separation between configuration and code. You should think about the space of configuration -- of domain logic -- and the space of application code, of the systems that enable that domain logic to exist. These two spaces should be separate, to allow flexibility, but they are there exists a transformation between them that is isomorphic.

You should think of elos definitions as a basis for the application code. Here we depart slightly from our algebraic analogy of vector spaces. But the idea of an isomorphism is the same. These definitions serve as the basis which code generation or other systems use to enact the actual program.
