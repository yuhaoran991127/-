## 11.24 笔记

### cmder使用

shift + e : 纵向分屏(自己配置)
shift + o ：横向分屏(自己配)
ls，dir

- cd <目录>
- mkdir 新建文件夹: mkdir git
- touch 新建一个文件： touch 1.cpp

### github的入门

#### 1. github注册

#### 2. 本地连接到github

- 创建仓库

- 复制仓库代码

  > https://github.com/yuhaoran991127/algorithm.git

- 连接远程仓库

  > ```powershell
  > git remote add origin https://github.com/yuhaoran991127/algorithm.git
  > ```

- 复制别人或者自己的仓库到本地

  ``git clone https://github.com/yuhaoran991127/algorithm.git``
  Cloning into 'algorithm'...
  remote: Enumerating objects: 3, done.
  remote: Counting objects: 100% (3/3), done.
  remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
  Unpacking objects: 100% (3/3), done.

- 发生了修改，更新到远程仓库

  - ``git add .``
  - ``git commit -m "Update"``
  - ``git push origin master``

- 查看分支

  ``git branch``
