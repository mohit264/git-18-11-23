When merge conflict doesn't need to solve judiciously i.e. 
either
1. we are keeping current branch changes
	(current branch = HEAD) and resolving merge using "Keep mine" option 
OR
2. We are keeping incoming branch change (incoming = the branch which we are interested in merging in current context "master")
	and resolving merge conflicts using "Keep theirs" option
In both the cases the new commit will not be created! 
Merge != new commit always

In our case new commit is created because after careful consideration between the changes the call has take judiciously to 
include both change in branch.txt file and hence file is modified which created new commit.
