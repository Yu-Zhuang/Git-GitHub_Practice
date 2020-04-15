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

---
# MarkDown語法
	語法筆記

## 標題
	大標題: # 標題
	次標題: ## 次標題
	   h3: ### (到h6 依序加#)

## 圖片 
	![替代文字](路徑)
![image](./image.png)

## 強調
	斜體: *文字*
	粗體: **文字**
	粗斜體: ***文字***
*斜體* **粗體** ***粗斜體***

## 放程式碼
	用縮排 tab
	或是 ```去包 (開頭```加程式語言可以highlight文字)
```javascript
let hi="hello javascript";
console.log(hi);
```
## 連結
	[連結文字](連結地址)
	ex: [youtube](https://www.youtube.com)
[youtube](https://www.youtube.com)

## 引用
	一級引用: >文字
	二級引用: >>文字
>一級引用
>>二級引用

## 分割線 與 列表標記
### 分割線
	---
### 列表標記
	1.
	2.
	3.
	*
	*
	*
---
1.
2.
3.
*
*
*
---
