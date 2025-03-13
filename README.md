# howtousegithub
Tutorial on how to use git and github


## Initialize the repo inside the desired folder
```
git init
```
## Add the files
```
git add .
```
> This will add the files in current directory to git
## Commit the changes
```
git commit -m "Commit Message"
```

## Add the remote url
```
git add remote origin https://github.com/ibrainscit/yourreponame
```

## Push(upload code into github)
```
git push origin main
```

## After this the code will be uploaded just refresh the github page 

## Using vscode
### Step1 - click on shown place
![Step1](images/step1.png)


## Step2 Type your commit message message and click on commit and then click on sync changes

![Step2](images/step2.png)




## How to update to new changes

### Add the changes 
```
git add .
```

### Commit the code
```
git commit -m "Update message"
```

### Push code to github
```
git push origin main
```

## Install git
```
sudo apt install git
```

## Install gh
```
sudo apt install gh
```

## Login using gh
```
gh auth login
```
* select github.com
* HTTPS
* type the personal token
### once this is setup youll be authenticated 
