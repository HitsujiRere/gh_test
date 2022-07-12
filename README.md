```
PS D:\products\test> tree /F
フォルダー パスの一覧:  ボリューム DATA
ボリューム シリアル番号は EEBE-D0D9 です
D:.
├─test1
│  └─test4
│          test.txt
│
├─test2
└─test3
        test.exe

PS D:\products\test> git init
Initialized empty Git repository in D:/products/test/.git/

PS D:\products\test> git add .

PS D:\products\test> git commit -m "1st commit"
[master (root-commit) 5b01bce] 1st commit
 2 files changed, 1 insertion(+)
 create mode 100644 test1/test4/test.txt

PS D:\products\test> git remote add origin https://github.com/HitsujiRere/gh_test.git

PS D:\products\test> git push origin master
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (7/7), 17.58 KiB | 8.79 MiB/s, done.
Total 7 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/HitsujiRere/gh_test.git
 * [new branch]      master -> master
```