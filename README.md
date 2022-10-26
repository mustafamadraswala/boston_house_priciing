# Boston_House_Pricing
End to End Machine Learning Implementation


## Software And Tools Requirements

1. [Github Account](https://github.com)
2. [HerokuAccount](https://heroku.com)
3. [VSCodeIDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

### Create a new environment
```
conda create -p venv python==3.8.8 -y
```
```
conda activate venv/
```

### Create and Install requirements.txt
```
pip install -r requirements.txt
```

### Setup your Github account
```
git config --global user.name "Mustafa Madras"
```
```
git config --global user.email "museychamp@gmail.com"
```

### Push all the changes and code to Github -
Add all the files to github - 
```
git add .
```

Check status of your files
```
git status
```

Commit all the files to github by pushing the fies from local to  thestaging environment -
```
git commit -m "This is my first commit includes requirement.txt and readme.md file"
```
or 
```
git add . && git commit -m "This is my first commit"
```

Push this to github -
```
git push origin main
```

### Excecute the LinearRegression.ipynb file to get the 2 pickle models
### Create a python file for your flask application
```
touch app.py
````

### Create a basic web appplication template using HTML -
Create a tempelates folder - 
```
mkdir templates
```
touch templates/home.html
```

### Excecute the file app.py in cmd
'''
python app.py
'''

### Push everything to Github

### Deploy application to the cloud - Heroku
#### Create a Procfile which excecutes some commands as soon as the app starts
Code in the Procfile






