This is an attempt to resuscitate the Alchemy2 project.

Alchemy 2.0 includes the following algorithms from the original Alchemy system:


* Discriminative weight learning (Voted Perceptron, Conjugate Gradient, and Newton's Method)
* Generative weight learning
* Structure learning
* Propositional MAP/MPE inference (including memory efficient)
* Propositional and lazy Probabilistic inference algorithms: MC-SAT, Gibbs Sampling and Simulated Tempering
* Lifted Belief propagation
* Support for native and linked-in functions
* Block inference and learning over variables with mutually exclusive and exhaustive values
* EM (to handle ground atoms with unknown truth values during learning)
* Specification of indivisible formulas (i.e. formulas that should not be broken up into separate clauses)
* Support of continuous features and domains
* Online inference
* Decision Theory


The key new feature of Alchemy 2.0 is lifted inference algorithms (both exact and sampling-based). Specifically, it includes the following inference algorithms:

* Probabilistic theorem proving (lifted weighted model counting)
* Lifted importance sampling
* Lifted Gibbs sampling

By using Alchemy, you agree to accept the license agreement in license.txt

src/ contains source code and a makefile.
doc/ contains a change log, and a manual in PDF, PostScript and html formats.
exdata/ contains a simple example of Alchemy input files.
bin/ is used to contain compiled executables.

Please refer to the change log at http://alchemy.cs.washington.edu/
for the latest changes to Alchemy.
