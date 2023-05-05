# IronScheme
## Hello world in IronScheme programming language

### IronScheme is an implementation of the Scheme programming language targeting the Microsoft .NET Framework. IronScheme is a complete rewrite of IronLisp, incorporating lessons learnt while developing IronLisp.

### IronScheme was planning to build upon the Microsoft Dynamic Language Runtime, but decided to abandon this idea because the DLR branch the project used became out of sync with the trunk, and also because the DLR, according to the developers, could not support the majority of the Scheme's requirements.

### IronScheme eventually made a limited use of its own version of the Microsoft's DLR, but it had to patch it to be able to implement some required Scheme features like tail call elimination.