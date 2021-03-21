### 基本 shell 命令使用
敲完命令直接回车就是执行命令，命令的关键字前后需要隔开
- ls 命令   
  查看当前目录下的所有内容(不包括隐藏)  
  参数 -a 查看隐藏文件

- pwd 命令
  查看当前所在位置并打印，一般用来复制路径

- cd 命令 后面跟着地址(相对路径)  
  `cd + 路径(必须是文件夹)`     
  跳转目录
  - ../     返回上一级目录
  - ./ 当前目录
  - /   
  - ~  这个目录存放的是一些软件的配置信息

- touch 命令
  `touch + 文件名或者路径加文件名`   创建的时候必须带上后缀名
  新建文件

- mkdir 命令 
  `mkdir + 文件夹名或者路经加文件夹名`
  新建文件夹

- rm 命令
  `rm + 文件或文件夹的名称`
  删除文件
  - 参数 `-r` 删除文件夹 只有加了改参数才能删除文件夹
  - 参数 `-f` 强制删除  多个参数可以连起来写 例如  -rf (有的时候可能也不好用)

  ```shell
  rm -rf ./*   强制删除当前文件下的所有内容 
  ```

- mv 命令    
  `mv + 文件或文件夹 + 路径/新的名字`
  剪切文件或文件夹还有重命名,(移动到当前目录就是重命名)
  ```shell
  mv 测试.txt ../aaa/test.txt  重命名
  ```

- cp 命令
  `cp + 文件或文件夹名 + 新的名字` 拷贝
  复制文件或文件夹还有重命名

- `cat 文件名` 查看当前文件内的内容

- clear 清屏


##### 命令行中的快捷键
- ctrl + c 结束当前命令,终止命令，重新开始
- tab 自动补齐文件以及文件夹或者命令的名称
- 直接回车是执行输入的命令
- clear 是清屏命令
- 键盘上的方向键上下是查看历史记录，左右是调整光标位置,上下箭头 返回输入历史记录
- 命令行内的复制粘贴不可使用 ctrl + c  和 ctrl + v ，使用鼠标右键