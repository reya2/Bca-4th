# protfolio
this is my first git repository
author-shreaya sapkota
a. frist ma if you make a folder git doesn't know about that floder so you have to initialize(git init  creat a new  git repo )aba git knows that there is a folder but it doesn't manage folder it is untracked,how to check(git status) and add (git add name),commit( git commit -m somemessage)
to check status  and you want only main point(git status -s)/(git status)(kati oota file xa kun tracked xa kun untracked xa)don't come anythting in commit file(status=talk about stage and changes9(before and after commit))
to check how many checked point or commit (git log )=detail
(git log --oneline)=specific (summarize) (commit stage/histories)
(git log --graph)=branch
{workflow}
github repo->clone->change->add->commit->push
{branch}
1.code to clone repository
```bash
git clone https://github.com/reya2/protfolio.git
```
2. After creating file we need tio init git
```bash 
git init
```
3.opening the git in vs code(to know current checked piont)
```bash
 git log --oneline
 ```
 4. make a file name(.gitignore)write the file you want to ingore in side that
 5.to reset or to go back to previous saved point for delet(there are 3 types hard,mixed,soft)
 ```bash
 git reset --hard HEAD~1
 ```