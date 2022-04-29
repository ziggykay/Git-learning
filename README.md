# First Git

# GIT 指令:

git config user.name ⇒ 顯示用戶名稱
git config user.email ⇒ 顯示用戶信箱

git init ⇒ 
git status ⇒查看目前git 狀態
git log ⇒ 查看git 歷史紀錄
git reflog ⇒ 查看git 詳盡歷史紀錄

git clone “url” ⇒ 在當前目錄下複製現有儲存庫
git add “filename” ⇒ 新增檔案至暫存區域 
git add *.test ⇒ 將所有副檔名為test的檔案新增至暫存區域
git add .⇒ 新增所有更動過的檔案至暫存區域
 
git reset “file” ⇒ 將檔案自暫存區移除
git reset “file” --hard ⇒ 將所有已追蹤檔案還原
git reset “sha1-code” --hard ⇒ 還原至特定步驟(需搭配git reflog取得sha-1)

git commit -m “message” ⇒ 提交檔案並附上訊息
git commit ⇒ 若不打m 則會開啟nano編輯器, 可輸入多行註釋
git commit -am “message” ⇒

git reset --hard<commit> ⇒
git reset --hard origin/master ⇒

git push
git pull

git branch
git checkout  “name”
git checkout -b “name”
git merge “name”
