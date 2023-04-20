### git学习笔记

1. 操作

   - 克隆远程项目到本地

     ```
     git clone /url/
     ```

   - 修改并提交到本地仓库

     ```
     git status # 可以看到修改的内容
     git add /file/ # 保存修改到本地库
     git commit # 将改动后的文件提交到版本库
     ```

   - 推送到远程仓库

     ```
     git remote -v # 得到远程仓库地址
     git push # 将本地仓库推送至远程仓库
     ```