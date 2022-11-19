## Boston_HousePrice
### Softwares and Tools required

1. [Github Account](https://github.com)
2. [VS Code IDE](https://code.visualstudio.com/download)
3. [Git CLI](https://git-scm.com/downloads)
4. [Heroku Account](https://www.heroku.com/)

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
## Steps to commit on git
- Let's add any file so we can put into the git 
    ```
    git add requirements.txt #add single file
    git add . #add all files
    git status #check file status
    ```
