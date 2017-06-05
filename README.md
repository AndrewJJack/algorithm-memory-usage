# algorithm-memory-usage
Implementing a simulator to study the working set sizes of programs running in virtual memory. The driver program will be a bash script sim that accepts the following three command line parameters (in this order):
 - The page/frame size specifed in words  
 - The window size for the working set model. 
 - The name of the process to run. 
Note that sim is the only script, and all else is implemented in C. The name component is such that it allows sim to handle an exchangeable process function implementing an algorithm whose working set behavior you will want to investigate.
