# Git 學習筆記
###### tags: `git`

---
###  Git 使用者相關
第一次使用Git時，需設定使用者名稱與信箱
```
git config --global user.name "user-name"
git config --global user.email "user-email"

顯示使用者名稱
git config user.name
顯示使用者信箱
git config user.email

```
---
### 建立 Git 專案
初始化Git，將檔案夾設定為Git專案
```
% git init 

指定資料夾
% git init {directory-name} 
```
複製現有專案的方式
HTTP網址複製:
```
% git clone url
```
例：以 HTTP 方式自github複製專案
```
% git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```
例：以 SSH 方式自github複製專案
```
git clone git@github.com:YOUR-USERNAME/YOUR-REPOSITORY
```
:::danger
!! 2021年八月後，自github上複製專案將需要輸入 access token
:::

---
### 查看 git 狀態
```
% git status

歷史紀錄
% git log 
```
---
### 新增檔案至 暫存區(stage)

stage

```
% git add {filename}
```

### 新增檔案至分支(repository)
```
% git commit -m "commit-message"
```
若只輸入`git commit`則將開啟編輯器，git會請你輸入提交信息

---
### 推送
```
git push
```

### 分支

```
查看目前分支
% git branch 

創建分支
% git branch {branch-name} 

前往分支
% git checkout {branch-name}

將分支合併
% git merge {branch-name}
```

### git pull

抓取分支
```
git pull

git [-C <path>] pull
```
