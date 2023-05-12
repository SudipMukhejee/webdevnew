


## Deployment
first you have to open the local folder in git bash and type

```bash
  git init
```
first you have to `fork` the repo
then you have to `clone` the repo
```bash
git clone https://github.com/<your_user_name>/shorto_url_shorter.git
```
Add a reference(remote) to the original repository.
```bash
git remote add origin https://github.com/vinyashegde/shorto_url_shorter.git
```
### inspite of `origin` you also give any name

Check the remotes for this repository. 
```bash
git remote -v
```

to add file to staging area
```bash
  git add .
```
To includes all the files that are in the staging area
```bash
  git commit -m "first commit"
```
Track your changes.
```bash
  git status
```
Push the committed changes in your feature branch to your remote repo.
```bash
  git push -u origin master 
  or
  git push
```







