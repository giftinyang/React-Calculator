# React Calculator
### Requirements
<hr>
To run this app you will need Node.js installed on your environment.

### Node
[Node](https://nodejs.org/en/download/) is really easy to install and it includes  the popular package manager [NPM](https://www.npmjs.com/) . When you install Node, run this command

    $ node --version
    v10.16.3
    
    $ npm --version
    v6.9.0

#### How to Install Project

    $ git clone https://github.com/giftinyang/React-Calculator.git
    $ cd React-Calculator
    $ npm install
npm install checks the package.json file and installs node modules based on the dependencies used in the project.

#### How to make changes and host on Netlify
To host on netlify, you have to push the project to github and then host on netlify. Let's walk through those steps.
##### Push to GITHUB
 You have to be in the projects directory and have [git](https://git-scm.com/) installed and you also need a [github account](https://github.com/).

    C:\Users\FELL\Desktop\React-Calculator

    
Now type the following commands: 

    $ git init
    $ git add .
    $ git commit -m "Initial Commit"
Now go to your  [github](https://github.com/) and follow the steps shown below:

 - Create New Repo
	- Click on the New button
	- ![](https://res.cloudinary.com/dinpc6uvd/image/upload/v1568120641/screencapture-github-2019-09-10-14_02_30_1.png)

- Give the repo a name. I called mine my-react-project
	- ![N](https://res.cloudinary.com/dinpc6uvd/image/upload/v1568120886/screencapture-github-new-2019-09-10-13_53_31.png)
Forget the Description input field (this generates a Readme.md file).
- Click on the Public radio button and  click the `Create repository` button.

- Copy the remote repo link
	- ![enter image description here](https://res.cloudinary.com/dinpc6uvd/image/upload/v1568121216/screencapture-github-giftinyang-my-react-project-2019-09-10-13_53_56.png)

Now after copying the link, go back to your terminal and type these commands.

    git remote add origin https://github.com/<your-repo-name>/my-react-project.git

If you're using github for the first time, you might have this error message

    fatal: unable to auto-detect email address
To fix this, you'll have to set your git credentials. Type these commands

    $ git config --global user.name "your-github-username-here"
    $ git config --global user.email "your-github-email-here"
Alright! Now we've setup our git environment, let's PUSH to the remote repository.

    git push -u origin master
If you've reached this stage, then you\'re ready for deployment. Let's deploy to Netlify.

#### Deploying to Netlify
Go to netlify.com and if you don't have an account, create one.

- ![enter image description here](https://res.cloudinary.com/dinpc6uvd/image/upload/v1568122050/screencapture-app-netlify-teams-giftinyang-sites-2019-09-10-14_26_45.png)
	- Click on the `New Site from Git` button.
- ![enter image description here](https://res.cloudinary.com/dinpc6uvd/image/upload/v1568122334/screencapture-app-netlify-start-repos-2019-09-10-14_29_24.png)
- Select the repository name
- ![enter image description here](https://res.cloudinary.com/dinpc6uvd/image/upload/v1568122285/screencapture-app-netlify-start-repos-giftinyang-React-Calculator-2019-09-10-14_30_03.png)
- Click on  Deploy Site
- ![enter image description here](https://res.cloudinary.com/dinpc6uvd/image/upload/v1568122285/screencapture-app-netlify-sites-brave-visvesvaraya-4e4248-overview-2019-09-10-14_30_29.png)

- ![enter image description here](https://res.cloudinary.com/dinpc6uvd/image/upload/v1568122588/screencapture-app-netlify-sites-brave-visvesvaraya-4e4248-settings-general-2019-09-10-14_30_44.png)
- Change Site name to name of  your choice.


### And there your Calculator app is live.
Check my [Calculator App here...](https://giftcalculator.netlify.com/)