## Understanding of formal methods and model checking ##

Zhu Shuncheng  13126183       Group C

**Formal Methods**

Formal methods can be part of the solution if imprecise designs and implementations that deviate from product specifications or design intentions are the causes for faults. Formal methods can prevent injection of certain defects into the software system.

Formal methods cannot guarantee perfection for software, but only assure it with respect to the formal specifications verified or the properties checked. In general, formal methods are suitable to stable product development and market environments, where product requirements can be captured into formal specifications and remain fairly stable thereafter to allow for later refinements and verifications.

**Model Checking**
Model checking is an approach that automatically or algorithmically checks certain properties for some software systems.



- A software system is modeled as a finite-state machine (FSM), with some property of interest expressed as a suitable formula, or a proposition, defined with respect to the FSM. Ideally, this FSM and the propositions are both developed during the software specification process, much like the use of formal specifications in various formal methods.



- The model checker is a software that runs an algorithm to check the validity of the proposition. If it is checked to be true, a proof is said to be produced. Otherwise, a counterexample is given, much like a failed test case that can be analyzed further for defect fixing.

