<<<<<<< HEAD
# cd2023_demo2
=======
# cd2023_demo1
>>>>>>> local_demo1/main

以上就是典型的未處理的衝突檔案, 其中因為 cd2023_demo2 在 local 目錄時, 採:

git remote add local_demo1 ../cd2023_demo1

git fetch local_demo1

git merge local_demo1/main --allow-unrelated-histories

因此當 cd2023_demo2 原有的 README.md 檔案從 remote 名稱為 local_demo1 的倉儲中的 README.md 試圖合併時,  ======= 之前的內容完原有資料, 也就是舊資料, 而之後的內容則為新內容

https://stackoverflow.com/questions/9781729/how-to-combine-two-separate-unrelated-git-repositories-into-one-with-single-hist
