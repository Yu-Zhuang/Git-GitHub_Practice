this is a pratice about how to use Git and GitHub
總工作流程 step1~6 (沒談到branch情況下)
0. 剛開始第一次寫專案 有兩種情況:
情況一: git clone 遠端空間網址 本機目標資料夾 (要從遠端將已開始的專案下載到本機; 
情況二: 到網頁開一個repository; 後使用 git remote add 遠端空間網址
1. git pull origin(遠端空間名稱) master(遠端分支): 先更新自己的資料夾內容
2. work, programming
3. git status 查看
4. git add 檔名.副檔名 (或是用 git add .   可一次全加入追蹤)
5. git commit (或用 git commit -m”紀錄這次更新的內容”)
6. git push origin(遠端空間名稱) master(遠端分支): 將這次的更新上傳
其他常用指令:
1. git log: 查看紀錄
2. git remote -v: 查詢連結的遠端空間
3. git branch: 查詢分支

