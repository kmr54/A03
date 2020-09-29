# A03

Part 1: How to Use Webstorm with **GitHub**
 1.) Download **git** onto your machine by following this link: https://git-scm.com/downloads (clicking on blue download button chooses correct software for system)
 2.) Create a **GitHub** account: https://github.com/join
 3.) Create a new **repository** by clicking on the plus button at the top right corner of the page
    b.) Name it something relevant, such as IS117, check the "add README.md file" box, and make sure it is public
 4.) Download the student version of Webstorm from this link: https://www.jetbrains.com/student/
    b.) Create an account and use this to login to Webstorm once the download is complete
 5.) Connect your **GitHub** account with Webstrom by going to Settings>>Version Control>>Git and adding the .exe file for git from your ProgramFiles
 6.) Store your **GitHub** password in Settings>>Appearance and Behavior>>System Settings>>>Passwords, adding a location for it
 7.) To sync your **GitHub repository** with Webstrom, go to VCS>>>Get from version control>>>Git
    b.) For the URL, click on the green "code" button in **GitHub** and copy and paste that link into the URL section
 8.) Now create a Webstorm File
    a.) File>>>New>>>HTML>>>HTML5
    b.) Name it and select "Add to Git"
    c.) Write a **commit** message in the designated tab and select commit
 9.) Now you have to **push** the changes to **GitHub**. 
    a.) Navigate to VCS>>>Git>>>Push
    b.) Go to GitHub and confirm file was added
 10.) GitHub Pages transforms your **repositories** into a website. To create a page:
    a.) Go to settings and select master **branch** as a source. Your **repository** can contain different branches or sections within it
    b.) Copy and paste the Github.io link into your browser and see what it contains
 11.) You can also create files through **Git** Bash and commit them to **GitHub**:
      a.) After creating a folder to host your **GitHub** code, you can **clone your repository** with the command "git clone repourl reponame", where repourl is the link from step 7b and name is whatever you decide to name that **repository**
      b.) To add files to the **repository**, make sure you are in the repository first (cd repository)
      c.) nano newfile.php is the format to create a new file. The ".php" indicates it is a php file type and most likely will contain that code
      d.) Save file
      e.) Add file: git add newfile.php. Now Git is keeping the track of the files and knows it exists
      f.) Commit: git **commit** -m "committing the file". This will commit the file to the GitHub repo with the included commit message
      g.) This should prompt us to login to github.com. If you haven't already you'll need to configure your username and password
      h.) Your final command should be "git **push** origin master" to finally add the file to GitHub
      
Part 2: Glossary

Branch- a separate working version of your repository that will leave your master branch unaffected
Clone- a copy of your repository. Allows you to edit or create Git files outside of GitHub
Commit- a change to a file
Fetch- adds changes from the remote repository to your local working branch without committing them
GIT- an open source program for tracking changes in text files, works well for collaborations
Github- a version control service that keeps track of file changes
Merge- takes the changes from one branch (in the same repository or from a fork), and applies them into another.
Merge Conflict-  happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file
Push-  to send your committed changes to a remote repository on GitHub.com
Pull-  allows you to gather all changes to current file you're working on and updates it
Remote- version of repository hosted on server (Github.com)
Repository- contains all of a project's files and revision history

References:
1.) Introduction to Github and Webstorm ppt
2.) https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/github-glossary
      
