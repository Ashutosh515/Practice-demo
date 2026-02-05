# Practice-demo
practice git hub to push and pull
Steps to push code into the repository and then pull the code from the gitHub to ec2 instance.

commands for push code to github repository from localhost
- git init : _to initialise the git into the localhost/folders._
- git add * : _'*' in the end of the code for add all the relative file to add on the stage._
- git status : _to view status of the stage._
- git commit -m "comment related" : _commit the added code for._

Connect local repo to GitHub
- git branch -M main
- git remote add origin https://github.com/<username>/<repo-name>.git
- git push -u origin main

For Amazon Linux
- sudo yum update -y
- sudo yum install git nginx -y

Start web server
- sudo systemctl start nginx
- sudo systemctl enable nginx
