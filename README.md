# Boston-House-Pricing

### Software and tools requirements

1.[Github Account](https://github.com/)

2.[VS Code IDE](https://code.visualstudio.com/)

3.[Heroku Accout](https://heroku.com/)

4.[Git CLI](https://cli.github.com/)

Create new environment for the project
```
conda create -n venv python==3.10 -y
```
Activate the environment
```
conda activate venv
```
freeze requirements.txt file
```
pip3 freeze > requirements.txt
pip install -r requirements.txt
```
connect with git cli
```
git config --global user.name
git config --global user.email
```
commit all the files in git
```
1.  it add requirements.txt -- for adding particular file
    git add . --for adding all the files that needs to be commited
2.  git commit
3.  git push origin main
```
