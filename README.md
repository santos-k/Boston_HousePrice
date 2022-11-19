## Boston_HousePrice
### Softwares and Tools required

1. [Github Account](https://github.com)
2. [VS Code IDE](https://code.visualstudio.com/download)
3. [Git CLI](https://git-scm.com/downloads)
4. [Heroku Account](https://www.heroku.com/)
5. [Postman](https://www.postman.com/downloads/)

Getting-Started-The-Command-Line
- Open Terminal: VS Code > Terminal
    - Create a New Environment
        ```
        conda create -p venv python==3.7 -y
        ```

    - Activate environment
        ```
        conda activate venv/
        ```

## Libraries Requiremtns
- Create a file in same directory 'requirements.txt'
- Enter all the libraries in that file 
- Now, to install all the libraries in single command
    ```
    pip install -r requiremtns.txt
    ```


## Setup Git to Push on Git
- Set Name and email for Git
    ```
    git config --global user.name "Your Name"
    git config --global user.email "Your github email"
    ```
## 1. Steps to commit on git
- Let's add any file so we can put into the git 
    ```
    git add requirements.txt #add single file
    git add . #add all files
    git status #check file status
    ```

## 2. Create Stagging (ready to be pushed)
- In this step all the files are now ready to push over the Git, till here no file will upload to git
    ```
    git commit -m "First Commit requiremtns and readme file"
    ```
## 3. Push to Git
- Now final step to push over the Git and the files will reflects on git server
    ```
    git push origin main
    ```

# Create FrontEnd App
### Folder and files structures
- BOSTONHOUSEPRICE
    - venv
    - app.py
    - templates
        - home.html
    - regression_model.pkl
    - scaler.pkl
    - requirements.txt
    - .gitignore
    - LICENSE
    - README.md

## Deploy on Heroku Server
 - First create a filename 'procfile'
    ```
    web: gunicorn app:app
    ```
    