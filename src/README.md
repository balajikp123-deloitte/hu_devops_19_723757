# hu_devops_19_723757
Created for DevOps assignment.

This document describes the steps taken to complete the assignment.

Step 1: Configure password less authentication in the repo’s
Solution: Added passkeys as touch(Windows Laptop) and facial recognition(Mobile Phone)

Step 2: Clone the repo hu_devops_19_<employee_id> to your localhost.
Solution: git clone https://github.com/balajikp123-deloitte/hu_devops_19_723757.git

Step 3: Create a branch name git-assignment and start working on it, for all track assignments  all documents and code should be put on this branch. 
Solution: git checkout -b git-assignment

Step 4: Create a file named secrets that should have your gitlab username and password, this file should not reflect in git console while you push to git repository. 
Solution: Created a secrets file with gitlab credentials and added it in .gitignore to ensure it is not tracked by Git.

Step 5: Create a security.md file and enter the information how above secret file was handled.
Solution: Created a security.md file and explained how secrets file was handled.

Step 6: Create the document of the complete process in a file name README.md and push this file to the same branch.
Solution: Created a document named README.md and added all the steps to complete the assignment.

Comman Commands:
    # Clone a repository
    git clone <repository_url>

    # Create a new branch
    git checkout -b <branch_name>

    # Add files to staging area
    git add <file_name>

    # Commit changes
    git commit -m "commit message"

    # Push changes to remote repository
    git push origin <branch_name>

    # Pull changes from remote repository
    git pull origin <branch_name>

    # Check the status of the repository
    git status

    # View commit history
    git log