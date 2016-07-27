github其实就是git

gitbook editor是git+gitbook编辑器

### 一. 前面在mac机本地用到了：

1. gitbook editor

  gitbook editor里面是已经包含了git的。

2. gitbook 工具
  gitbook工具是用来将你的book转换成html或者pdf的。


### 二. gitbook editor+github+gitbook工具  VS gitbook editor+gitbook工具

区别就是github是可以推送到github上的

1. 如果你想要将你的newbook放到github上，首先必须保证你的github有一个仓库存放你的book，如果你的book在github上已经有了，就不需要新建，直接将修改的book 推送到github上即可。

  1. 方法一：直接在github上新建
  2. 方法二：用SourceTree去create一个新的

2. 如果github上的仓库已经有了你的book，而你的mac机本地没有，就先从github上clone下来

  1. 使用SourceTree去clone，或者直接使用命令：git clone https:\/\/github.com\/V-KING\/newBook1.git

  2. 使用gitbook editor打开newBook1目录，便可以继续编辑你的book

  3. 参照 [在mac上安装使用gitbook](chapter1.md) 使用gitbook



1. 注意区分gitbook editor的目录和 SourceTree的目录区别
2. 在SourceTree中可以多添加一个remote repository，这样你可以用SourceTree从你本地上pull到SourceTree的仓库，然后在用SourceTree 推送到github-master上
  1. Setting-&gt;Add -&gt; Remote name填写github-master -&gt; URL\/path中填写或者选择你在github上已有的仓库：https:\/\/github.com\/V-KING\/newBook1.git
  2. 从此后，github-master就代表了https:\/\/github.com\/V-KING\/newBook1.git


