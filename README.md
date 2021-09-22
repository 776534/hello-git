# hello-git
## H1 筆記
### 查看 git 的狀態
*$ git status*

### 把檔案加入
*$ git add test.txt*

### 提交這次的修改
*$ git commit -m "正確填寫這次 commit 的資訊"*

### 檢視這次修改的差異
*$ git diff*

### 已經加入過的檔案，又有修改的話，一樣要再 add 一次，才可以 commit
*$ git add test.txt*
*$ git commit -m "xxxx"*
### 針對已經加入過的檔案，可以直接用以下指令提交
*$ git commit -am "xxxxx"*

### 可以「反悔」加入暫存區
*$ git restore --staged login.html*

### 反悔剛剛的修改
*$ git restore login.html*

### 讓檔案回到某個特定版本
*$ git checkout <commit> test.txt*

### 讓檔案回復到前兩個版本
*$ git checkout HEAD~2 test.txt*
### 回到現在版本
*$ git checkout HEAD*
  ### 查看提交紀錄
*$ git log*

### 查看特定檔案的紀錄
*$ git log <file>*

### 查看檔案修改細節
*$ git log -p a.txt*

### 可以搜尋關鍵字
*$ git log --grep="delete"*

### 查看內容是誰編寫的
*$ git blame test.txt*
  ### 檢視分支
*$ git branch*

### * 是標注你所在的分支

### 建立分支 
*$ git branch <branch-name>*

### 切換分支
*$ git switch <branch-name>*


### 如果兩個分支有提交過同一個檔案的修改，那就有可能發生衝突 confict
### 就只能人工修改，可能需要跟同事討論
### 解完衝突之後，就要再 commit 一次
### 建立 hello-git 檔案夾
*mkdir hello-git*
### 進入 hello-git 檔案夾
*cd hello-git*
### 建立檔案 test.txt
*touch test.txt*

ls
### 列出全部檔案（列出隱藏檔）
*ls -a*
### 以完整格式列出檔案
*ls -l*
### 以完整格式列出所有的檔案
*ls -al*

### 檢視檔案內容
*cat test.txt*
  
  
Windows | MacOS/Linux | 說明
 --- | --- | ---  
 cd |	cd |	切換目錄 change directory
 cd |	pwd |	顯示目前所在路徑
dir |	ls|	列出目前檔案夾的檔案列表 list
mkdir |	mkdir |	建立新的檔案夾 make dir
copy |	cp |	複製檔案 copy
move |	mv |	移動檔案 move
del |	rm |	刪除檔案 remove
cls |	clear |	清除畫面上的內容
cat |	cat |	印出檔案內容
  
 
