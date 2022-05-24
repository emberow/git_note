# git_note


git remote add <url>//連到遠端儲存庫
git branch <new-branch> //創建新branch
git branch <new-branch> <base-branch> //創建新branch base on <base-branch>

git init //初始化

//每次upload要做的事
git add . //添加當前目錄的檔案到暫存區
git commit -m "change something"
 
//正常push
git push
  

//push失敗可以先拉在推或強制推(不建議)/////////////////////////
git pull --rebase origin <branch> //當push失敗時可使用先拉在推
git push origin <gitlab branch>//將local commit上傳到gitlab
  
git push -f //強制覆蓋全部
////////////////////////////////////////////////////////////
  
  
git checkout <branch> //切換branch

git merge <branch> //將指定branch 合併到目前的branch

git branch -d <branch> //刪除指定分支
