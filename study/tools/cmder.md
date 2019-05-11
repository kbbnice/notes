#### cmder是世界上最好的工具



下载地址：[cmder官方下载地址](https://cmder.net/)



##### 为什么好用？

1. 你可以省去很多敲代码的时间，做更多的事情。
2. 心情会很好！



##### 看看代码：

1. 返回上一级：

   ![1557595902642](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557595902642.png)

2. 打开任意盘：

   ![1557595967668](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557595967668.png)

3. 直接打开某个软件：

   ![1557596127292](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557596127292.png)

是不是特别愉快？

还有：

`Linux` 的 `ll` 快捷方式：

![1557596232536](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557596232536.png)



是不是在 `windows` 发现了 `linux` 既视感？

不需要安装虚拟机，

不需要998.

只要下载一个 `cmder` .

骚操作马上带回家！



##### 废话不说看教程：

1. 首先：你需要下载 `cmder` 。

2. 其次，打开 `cmder` 的安装目录：（默认你是白银级以上的程序猿，已经知道怎么查找软件目录。）

3. 打开 `cmder` 目录下config文件夹：

   ![1557596482328](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557596482328.png)

4. 先备份一份config，以免出现bug无法挽救，只能重装。（但是cmder的下载真的很slow.)

   **user_profile.cmd**

5. 找到user_profile.cmd文件，打开。

   ![1557596562004](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557596562004.png)

6. 在 `user_profile.cmd`  里，前面的 `::` 开头的都是注释，不用管。

   在 `@echo off` 之前一行加上 `@J：` ，这个 `@` 符号后面跟着的是你打开 `cmder` 时候默认的盘，我的是默认 `J:`  盘：

   ![1557596936074](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557596936074.png)

   *保存，重启 `cmder` , 效果如图，打开 `cmder` 默认进入 `J：` 盘（务必重启 `cmder` ）：

   ![1557596970835](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557596970835.png)

7. 到这里，结束了 `user_profile.cmd`  的编辑，下一步，正式开始骚操作的时候了：（前半部分真特么没营养）。

   **user_aliases.cmd**

   同样是 `config`  目录下， 打开：`user_aliases.cmd`  文件：

   ![1557597583650](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1557597583650.png)

   在 `Add aliases below here`  （在这后面添加命令的别名）这行 `English` 之后，你看到了什么神奇的事情了吗？

   没错，这些都是快捷方式。等号前面是你规定的缩写，等号之后，就是原本你需要老老实实打出的代码。

   **开始造作吧！**

8. 

   a. 

   如果你想设置打开某个盘或者某个盘,比如C盘：

   ​	直接 `c` = `cd /d C:\`  ;

   b.

    如果你想打开某个软件，比如你常用的vs code 或者 Hbuilder 等等之类的编辑器，或者任何不可描述的软件：

   ​	直接在系统找到所需要运行的` .exe` 文件, 复制该文件所在的**绝对路径**，再加上这个exe文件的全称。如：我找到我的vs code 所在的根目录 `G:/Program Files (x86)/Microsoft VS Code`   ， 它的exe 文件叫做： `Code.exe `  ， 此时，我想用 `vs` 作为这个软件的快捷打开方式，则写法如下：

   ​	`vs="G:/Program Files (x86)/Microsoft VS Code/Code.exe"`

   ！！！请记得加**双引号**，否则，会报错。如果不加双引号，它只识别第一个空格前的字符串。

   会报错如下：

   ​		`'G:/Program' 不是内部或外部命令，也不是可运行的程序或批处理文件。`

   

9. 写完所有骚操作之后，保存。

10. 重启cmder。



是不是不需要998？ 就爽到家？



-----完-----









 

