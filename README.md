# Daily_Logs


Daily Logs of D&amp;D employees

## Pushing Logs to Git

- To set origin to the Daily Logs repo 
```
git remote add origin https://github.com/Artribe-BPO/Daily_Logs.git
```
#### or the one below if the above doesn't work
```
git remote set-url origin https://github.com/Artribe-BPO/Daily_Logs.git
```
- To add your file to the list of files to be pushed to the repo
```
git add <fileName>
```
- To check which files are ready to be sent
```
git status
```
- Before pushing these files, make a new commit with the naming convention "Day Date Month"

```
git commit -m "Tuesday 4 January" 
```
- To finally push these files onto the repo,

```
git push -u origin master
```

## Token Auth
- You'll be asked for authorization before you are allowed to push however

### username: Artribe-BPO

- For password, you'll have to generate your token. To do that, go to the link below

 ### https://github.com/settings/tokens
- Click on Generate New Token Button
- Add "YourName Daily Logging Token" as Note
- SetExpiry to whenever you want it to expire
- Check the "repo" option and at the bottom click "Generate token"
##### Copy the token and send it to your Manager or save it somewhere because it won't be visible again
- Copy Paste this token in the password field and you are good to go

### password: -Generated Token-

## Error 
Updates were rejected because the remote contains work that you do
hint: not have locally.

This means that the files uploaded on git has some changes that git cannot detect on the same files you have on your system
This can be solved by 
```
git pull origin master
```
Then you can continue with the above method of pushing files to git
