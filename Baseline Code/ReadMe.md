functions.cpp => File contains all the functions needed to run the file. 

headher.h => header File that contains the function prototypes.

decisoinTree.cpp => File contains the main() function and accepts 2 command line arguments: Training File and Testing File


## Changes Made to the original

header.h => LINE 31 : added depth argument in buildDecisionTree

functions.cpp => LINE 86 : hardCoded maxDepth as 3
              => Can take it as a command line argument.

              => LINE 323 : hardCoded length of data instances as 200
              => Will need a variable to count total instances.
              
decisionTree.cpp => LINE 73 : Added Printing statement to see the decision tree.
                 => Needs to be removed for benchmarking purposes.
