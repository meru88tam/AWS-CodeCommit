# To create a new repository named “My-Repo” in AWS CodeCommit, 
Navigate to “CodeCommit” via the AWS Management Console, click on “Create repository”, and fill in the required fields. Upon creation, you’ll be directed to the repository page.
A console connection enables web browser access to the instance, automatically executing commands to switch to the user’s home directory upon connection.

To sync your local code with AWS CodeCommit, initialize a Git repository in your local IDE, add and commit your code files, then link your local repository with the CodeCommit repository using the Git URL. Push your local code to the CodeCommit repository using “git push”.
To authenticate with Git repositories using the AWS credential profile, set up the Git credential helper in your command line interface. 

# To clone your AWS CodeCommit repository with HTTPS
•	Clone a repository: You can copy the HTTPS URL of your repository from the AWS CodeCommit console and use the git clone command to clone it to your local machine.
•	Copy a command: You can copy the git clone command from the document and paste it into your terminal session. You need to replace the placeholder value with the actual URL of your repository.

# To modify the code and make your first commit in your local repository, do these steps:
•	Go to the "My-Repo" directory by executing this command:
•	Copy
•	cd ~/My-Repo
•	create two files in your local repository 

# To upload your first commit from your local repository to your AWS CodeCommit repository, follow these steps:
Run the following command:
Copy
git push -u origin master

You now have successfully:
•	Created a code repository using the AWS CodeCommit Management Console
•	Created a local code repository on your Linux instance using git
•	Synchronized a local repository with an AWS CodeCommit repository
