# CacheReplacement_CS622
#### Study of State-of-the-art Cache Replacement Policies

An empirical evaluation and analysis of few state-of-the-art cache replacement policies. This was a course project done during *2019 Sem-I* offering of **CS622 Advanced Computer Architecture** by *Prof. Mainak Chaudhuri*, at IIT-Kanpur.  
In this project, comparitive analysis of three state-of-the-art cache replacement policies is done using cache statistics collected by running SPEC CPU benchmark traces from *CRC2*.  
The following three policies were analysed - 
* Dynamic Insertion Policy
* SHiP: Signature-based Hit Predictor for High Performance Caching
* Hawk-Eye Replacement Algorithm  
  
*ChampSim-CRC2* & *C++* was used for implementing the policies, and running the simulations. Only DIP was implemented from scratch, while the other two were already provided.  
The following SPEC benchmark traces were used for generating cache statistics -
* astar
* xalancbmk
* omnetpp
* gromacs
* perlbench
* gcc  
  
The results generated were used to perform analysis over the performance of the policies, and to infer the underlying probable causes of their performance.   
A report about the inferences obtained from the study has been included in the repository for reference.
