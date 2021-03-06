# BasicSimRank

A simple implementation of the basic simrank algorithm.

### Run istruction
- Install JDK http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
- Install Eclipse https://www.eclipse.org/downloads/?
- import project in Eclipse 
- copy the data you want to compute in `graph.txt`


#### Run configuration for Eclipse
In this project we use 3 arguments from cmd, set this in `Run-> Run Configurations`

1. the name of file containing the data you want to compute, by default is `graph.txt`
2. the costant `C`, which can be thought of either as a confidence level or a decay factor in Widom,Jeh paper `C=0.8`
3. the number of iteration, we have the same result of Widom,Jeh paper if we set number of iteration= 7


#### Run configuration from command line

1. download `simrank.jar`
2. download `graph.txt` 
3. open cmd an go to the directory where you downloaded the files
4. type `java -jar simrank.jar graph.txt 0.8 7`


##### References
Jeh, Glen, and Jennifer Widom. "SimRank: a measure of structural-context similarity." _Proceedings of the eighth ACM SIGKDD international conference on Knowledge discovery and data mining_. ACM, 2002.
http://ilpubs.stanford.edu:8090/508/

