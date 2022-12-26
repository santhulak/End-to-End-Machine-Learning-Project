# End-to-End-Machine-Learning-Project

Requirement:

1. Github Account : https://github.com/
2. Heroku Account: https://www.dashboard.heroku.com/login
3. VS Code IDE:https://code.visualstudio.com/download
4. Git cli : https://git-scm.com/downloads


Creating Conda environment

```
conda create -p venv python==3.7 -y
```

OR

```
conda activate venv
```

```pip intall -r requirements.txt
```
To Add files to git

```
git add .
```
OR

```
git add <file_name>
```

Note: To ignore file or folder from git we can write name of file /folder in .gitignore file
To check the git status

```
git status
```

To Check all version maintained by git

```
git log
```

To create version/commit all changes by git

```
git commit -m "message"
```

To send version/changes to github

```
git push origin main
```

To check remote url

```
git remote -v
```

To set CI/CD Pipeline in Heroku we need 3 informations

1. HEROKU_EMAIL
2. HEROKU_API_KEY
3. HEROKU_APP_NAME


To create a Docker File:
Click new file -> type -> Dockerfile


create a new file ->.dockerignore ->mention the files that is not needed in docker

Build Docker image

```
docker build -t <image_name>:<tagname>
```
Note: Image name for docker must be lowercase

To list docker image

```
docker images
```
Run docker image

```
docker run -p 5000:5000 -e PORT=5000 imageid

```
to check running container in docker
```
docker ps
```
to stop docker container
```
docker stop <container_id>

```