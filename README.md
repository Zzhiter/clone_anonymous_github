# clone_anonymous_github

clone / download repositories from anonymous.4open.science

```
git clone https://github.com/kynehc/clone_anonymous_github.git
cd clone_anonymous_github
python download.py --url https://anonymous.4open.science/r/****/ --dir savepath/
```
pls make sure there is a slash in the end of url.

example:
```
➜  clone_anonymous_github git:(main) python3 download.py --url https://anonymous.4open.science/r/VulEUT-38B3 --dir ~/chatgpt-reachability-analaysis/
[*] cloning project:VulEUT-38B3
[*] downloading files:
[*] files saved to:/home/zhangzhe/chatgpt-reachability-analaysis/
```

#### Acknowledgement

Thanks to [tdurieux's Anonymous Github project] (https://github.com/tdurieux/anonymous_github)
and [ShoufaChen's Anonymous Github project] (https://github.com/ShoufaChen/clone-anonymous4open)
