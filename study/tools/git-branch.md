#### git 分支：（初始没有冲突的）

1. 创建新的分支：

```
git checkout -b branch-name
//这行代码相当于：
git branch dev
git checkout dev

//返回的结果都是：
Switched to branch 'dev'
```

` git  branch `  加上 ` -b ` 表示创建并切换。



2. 查看当前分支： 

   ```
   git branch 
   
   //返回：
   *dev 
   master
   ```

3. 切换到其他分支：

   ```
   git checkout other-branch
   ```

   

4. 合并分支：

   ```
   git merge dev
   ```

   

5. 删除分支：

   ```
   git branch -d dev
   ```

   

6. 给分支改名：

   ```
    git branch -m pre-name new-name 
   ```





