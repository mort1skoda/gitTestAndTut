Branch has been renamed from master to main :::::

```
git branch -m master main
git fetch origin
git branch -u origin/main main
git remote set-head origin -a
```




## gitTestAndTut
### Branch: master
#### My private testing of git gh auth clone push pull

#### install git and github-cli
```
sudo pacman -Syu
sudo pacman -S git github-cli -y
gh auth login
```

#### create a folder for your repos:
```
mkdir -p ~/repo
cd ~/repo
```

#### clone:

```
git clone https://github.com/mort1skoda/gitTestAndTut.git
cd gitTestAndTut
```

#### open a file and do some work:
```
vim new.repo.txt.md
```

#### push your hard work onto github.com:
```
git status
git remote -v
git add new.repo.txt.md
git commit -m "short msg or I use $DATE"
git push
```

INFO:
=====
<pre>
If you call your file(s) filname.txt.md
all pre section boxes wil have the copy function!
</pre>

