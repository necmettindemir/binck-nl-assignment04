


----------------------------------------------

Assignment

4) We use git as a repository for our code. 

   Please share how you see an ideal git branching, given we use three stages 
   for continuous integration: dev, stag, prod. 

   How should versions work? 
   How should hot fixes be deployed?


----------------------------------------------

Design for  "dev, stag, prod" and "versions, hot fixes" ???


- For each release a new branch can be created 

- "New branching and merging strategy" should be predefined 

- Like features, hotfixes may have seperate branches


Look at LookAtMe_Prj04_Git_Branch.png for my approach.



----------------------------------------------



==== General Recommendations for Successful Coding & CI =====


- Many developers set up a CI server and assume they are doing CI!
  But CI is more than setting up a server.

- Code always must be kept releasable

- Code with bug must not be committed to any repository

- Each module in solution could have a release version and this release version info 
  could be seen by the end user

- Architectural capabilities are important for successful CI

  For example : Microservice approach may be better than others for CI.

  
- Development and motivation strategy is important

  For example : Pair programming may be better for CI

- The quality of code effects the CI. 

  It means that SOLID principles and some concepts such as KISS, DRY, etc are important for
  successful CI.

- Backward compatibility is important for successful CI.
  
- Many developers develop features, features are combined and we reach component,
  component take us to product

  This means portability and modularity of product are important to succeed in managing CI.





