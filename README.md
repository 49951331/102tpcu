##操作

每次修改好了以後，可以先將修改存入stage

`git add "檔名"`

若一次修改大量檔案，可以將所有檔案修改都add進去stage

`git add .`

只加修改過的檔案, 新增的檔案不加入

`git add -u`

之後commit提交一次的修改

`git commit -m "註解"`

另外也可以把git add與git commit用一個指令完成

`git commit -a -m "註解"`

改好了使用

`git push`

如果您在github上的版本較新，也可以輸入git pull
更新本地端的repo

`git pull git://github.com/49951331/102tpcu.git`

刪除檔案

`git rm "檔名"`

##開分支branch

確定本地分支

`git branch`

開新分支

`git branch "分支名稱"`

切換分支

`git checkout "分支名稱"`

合併分支

`git merge "分支名稱"`

刪除分支

`git branch -d "分支名稱"`



##密碼

密碼緩存
`git config --global credential.helper cache`

默認情況下緩存密碼15分鐘，可以使用以下指令將緩存設置為1小時（以秒為單位設置）
`git config --global credential.helper 'cache --timeout=3600'`

##gitflow
<a href= http://ihower.tw/blog/archives/5140>gitflow</a>

gitflow_github
<a href= https://github.com/nvie/gitflow/wiki/Linux>github</a>
