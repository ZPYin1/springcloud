# springcloud
springcloud-study


1. 学习git 上传

    1.1 安装git 设置密钥
        ssh-keygen -t rsa -C "[email]"  (本地，首次需要)

    1.2 在git上新建仓库

    1.3 在本地文件新建安装项目文件夹

    1.4 查询当前config
        $ git config --list

    1.5 添加相关参数
        git config --global user.name "[name]"
        git config --global user.email "[email]"

    1.6 克隆新建项目
        git clone git@github.com:ZPYin1/springcloud.git

    1.7 修改本地项目

    1.8 上传修改后的目录
        cd springcloud/
        git add .

        $ git status
        On branch main
        Your branch is up to date with 'origin/main'.

        $ git commit -m "first commit"
        
        $ git push origin main





