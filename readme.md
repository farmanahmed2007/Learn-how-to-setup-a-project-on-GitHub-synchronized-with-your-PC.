# Learn how to setup a project on GitHub synchronized with your PC.

This will help you build the project on github.com, and share your project with other developers.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.


### PuttyGen

This will give you a key to provide to all the developers to work on git project

```
- Download PuTTY from https://www.putty.org

- Create a Project Folder

- Run PuTTYgen

- After application opens click on Generate

- A green progressbar will start to run, you will have to move your mouse pointer below the green area so the progress keeps going

- Copy the generated code.

- Save Public Key, with any name on project folder

- Edit Public key and replace with the copied code

- Now Save Private Key, with any name on project foilder

```



### Repository on GitHub

A step by step series of examples that tell you have to get a github repository up and running

Follow each step correctly

```
- Goto github (https://github.com/) and hit Sign Up button.

- Create account and verify with your used email.

- Login  by Sign In button to your account.

- After that you are logged in, click on "Start a project" button.

- Enter "Repository Name", choose public for free version and hit "Create Repository" button.

```

Adding putty public key to github repository

```
- Goto User Icon on top of the page and select Settings from dropdown.

- Click on "SSH and GPG keys" located in left sidebar.

- Copy and Paste Public key generated from PuTTYgen in "SSH and GPG keys" start with "ssh-rsa" and ending with "rsa-key-(some number)"

- Then click on "Add SSH Key" button.

```

Now that you are done with adding PuTTYgen key follow these steps on your local PC

```
- Goto user icon on top of the page and from dropdown select "Your Profile"

- This will open the profile page will have all the repositories included to your github account.

- Now click on your reposiroty, it will open up a page, there you will see a green button "Clone or Download"

- Copy and save the link given under "Clone with SSH"

- Now Click on Use HTTPS

- Copy and save the link given under "Use HTTPS"

```


### Tortoise Git

This will help you get the project setup on your local Computer and communicate with the github repository.

```
- Create Project Folder on your PC.

- Right click and select "Git Bash Here".

- It will open up a command prompt

- Type "git clone command (space) (Use HTTPS link)" and hit enter from keyboard.

- The repository project folder will appear in your PC.

- Right click on project folder and select TortoiseGit > settings.

- This will open up the TortoiseGit Settings option on a particular folder to connect with the repository.

- Now click on Git > Remote from left pannel.

- Now you will see "origin" click on ot and paste in the push url that is "Clone with SSH" link that you coppied from github.

- Now in the same way browse for the Private key that was generated from PuTTYgen and saved in your project folder.

- Now hit Apply then OK.

- Create any file in project folder eg (readme.md).

- Right Click on project folder and hit "Git Commit -> master" ...

- It will pop open up a window

- Add Comments in top "Message" Section.

- Hit "Commit & Push"

```

That will be all for now to save a project up and running from your Personal Computer to github

## Authors

* **Farman Ahmed** - *Initial work*

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.
