# testingbysmit
This is just a testing repository focusing to learn basics git

## Create a GIT repository for your project
* Create a repository in your GitHub account. Give it proper name and description
* Goto that repository homepage in your GitHub and click on `<> code` > select `http` and copy the link.
* Goto your command terminal `cd` to the directory created for your project e.g. `cd priyanshu/testingbysmit`
* Enter command `git clone <http link that you copied>`
* It will ask for your username and password if it is PRIVATE repository. Enter the same as your gitHub. for e.g. username = PriyanshRaj30, password = whaterveryoucreated. You will find all the files of your repository in your local directory.
 
## Add content to your Repository
* Once your repository is created, goto the local repository in your pc and add/modify your content.
* To push back your content use below commands : 
```console
$ git add <name of files you want to add OR '.' for all changes>
$ git commit -m "write a msg in one line explaining what you did in this commit"
$ git push origin main
```