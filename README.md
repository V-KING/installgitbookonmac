# 在mac上安装使用gitbook

## 一. 安装gitbook

1. 安装npm

  1. npm是包含在nodejs中的，所以安装nodejs：https:\/\/nodejs.org\/en\/
  2. 安装gitbook：
    参考：https:\/\/github.com\/GitbookIO\/gitbook\/blob\/master\/docs\/setup.md\#install-with-npm

    sudo  npm install gitbook-cli -g 


### 二. 使用gitbook

1. 创建一个book

  cd \/your\_path\/newBook
  gitbook init
  gitbook build
  你会发现在\/your\_path\/newBook目录下多了一个\_book目录
2. 用鼠标进入到\/your\_path\/newBook\/\_book目录
3. 双击index.html

