- 第一步 : 去github 创建一个仓库
- 第二步 : git init 
- 第三步 : git config user.name "用户名称"
- 第四步 : git config user.email "用户邮箱地址"
  - git config --list 查看配置信息 (可选)
- 第五步: git add 文件名 把工作区的指定文件 提交到暂存区
  - git add . 或者这样子输入(.代表工作区所有文件)
- 第六步 : git commit -m "第几次修改随便输入"
- 第七步 : git remote add origin 地址复制github里面的内容
- 第八步 : git push origin master 每次往远程提交代码的命令
  - 苹果电脑有时候需要输入用户名 和 登录密码  操作过之后OK

修改信息后的修改:
1. git add .
2. git commit -m "第几次修改随便输入"
3. git push origin master
