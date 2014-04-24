## What are the basic concepts of DDG? ##

Zhu Shuncheng  13126183       Group C

**DDG(Data Dependency graph)**

In DDGs, each node represents the definition of a data item, such as a variable, a constant, and a compound data structure. The links in DDGs represent the D-U relation, or “is used by”.  That is, if we have a link from A to B, we interpret it as that the data defined in A is used to define the data in B.

Through DDG we can get data dependency analysis (DDA). In DFT, we are focusing on testing the coirrect handling of different data items involved in producing the final computational output through data dependency analysis(DDA).

Therefore, we can view a DDG as a logical graph where computational results 
are expressed in terms of input variables and constants through the possible use of some intermediate data items as nodes and related D-U relations as links. 

The relations modeled in DDGs are always D-U relations, or “is-used-by” relation. 

D-U relation: This is the normal usage case.  When a data item is used, we need to obtain (or “fetch”) its value defined previously


