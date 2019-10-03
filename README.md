Learning git branching

Case 1:
	* PC_A got 1 master branch and pushes to the repo
	* PC_B 	downloads the repo and creates a "login" branch and checkouts it,
			creating a new file and modifying a file that was also in master branch
	* PC_A then modifies a file and pushes to the repo
	* PC_B checkouts master branch and tries merging locally