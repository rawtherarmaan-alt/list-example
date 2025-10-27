 # Github and Git Bash tutorial
Step 1: 
    -Install the git bash to interact with github
    -link gitbash and github account
    -open git bash
    -first link the github username using command : git config --global user.name "github username"
    -second link your github email  address uaing command : git config --gloabl user.email "your github email address"


## Step2 (How to uplaod files to repository and create new repository) :
    -open the github account login
    -open the github dashboard and click on top nav +  sumbol and click new repository and give name to repo and create repository
    -copy the rpo link (ex: https://github.com/bhaskarAntony/list-example.git)

    -open which folder want uplaod open in file explorer and open the folder right click click more options and click git bash here
    -first initilize the git in our folder using command : git init  => enter
    -add all files to upload using command : git add . => enter
    -save added files to upload using command : git commit -m "any message got commit or save"
    -we are uplaoding this files first time so link this folder to any repository using command  : git remote add origin  your_repo_link(ex: https://github.com/bhaskarAntony/list-example.git)

    -finally upload the saved files to repo using command : git push -u origin master



### Step3 (how to update existing repo):
    -add all the files using command : git add .
    -save added files to upload using command : git commit -m "any message got commit or save"
    -finally upload the saved files to repo using command : git push -u origin master