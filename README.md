# Daily_Logs
Daily Logs of D&amp;D employees

### To generate your personal tokens to be allowed access to push logs onto the Daily_Logs repository
https://github.com/settings/tokens

- Tick the repo checkbox in the scope

- Set the token to expire whenever you want it to

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
git push -u origin main
```
