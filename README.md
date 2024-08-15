# PLP-Basic-Git-Assignment

Here's a document outlining the instructions for the assignment, including linking a local repository to GitHub, making changes, committing, pushing, and verifying:

Git and GitHub Assignment Instructions
Task 1: Link Local Repository to GitHub
Link Your Local Repository to the GitHub Repository

To connect your local Git repository to the GitHub repository you created, use the following command:

bash
Copy code
git remote add origin <repository-url>
Replace <repository-url> with the actual URL of your GitHub repository.

Task 3: Making Changes
Create a File

Inside your local folder, create a new text file named hello.txt.

Add a simple text message to the file. For example, write "Hello, Git!".

Committing Changes

Stage the Changes: Prepare the file for commit by staging it:

bash
Copy code
git add hello.txt
Commit the Changes: Save the changes to the local repository with a commit message:

bash
Copy code
git commit -m "Add hello.txt with a greeting"
Task 4: Pushing to GitHub
Push the Committed Changes

Upload the committed changes to your GitHub repository using:

bash
Copy code
git push -u origin main
Task 5: Verification
Verify on GitHub

Open your web browser and go to your GitHub repository.

Confirm that the hello.txt file and the commit message "Add hello.txt with a greeting" are visible in your repository.
