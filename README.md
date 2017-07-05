# fanzehuadehub
测试搭建远程仓库

配置Mac的SSH Key的公钥（用于限制提交）

在Mac上生成SSH Key（在终端输入下面指令）
cd ~/.ssh
ssh-keygen -t rsa -C "你的邮箱地址”
然后一直敲回车

然后就会在~/.ssh目录下生成SSK Key的秘钥对
id_rsa ：私钥，不可泄露
id_rsa.pub ：公钥，可以公开（将这个文件的内容粘贴到GitHub上）

利用cat指令可以查看文件的内容
cat id_rsa.pub
