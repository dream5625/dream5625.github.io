# github库的配置与上传（完成公网上传）




# __git库连接github__


## __git配置__

### 命令代码：

    cd mysite
    
    hugo --theme=LoveIt --baseUrl="https://dream5625.github.io/" --buildDrafts
    
    cd public
    
    git config --global user.email "1258851398@qq.com"
    
    git config --global user.name "dream5625"

<img src="/19.jpeg">

<img src="/20.jpeg">

<img src="/22.jpeg">

_________________


## __创建git仓库配置__

### 命令代码：

    git init

    git add .
    
    git commit -m "first push"

<img src="/21.jpeg">

_________________

## __完成连接__

    git remote add origin https://github.com/dream5625/dream5625.github.io.git
    
    git push -u origin master

<img src="/23.jpeg">

<img src="/24.jpeg">


## __查看上传__


<img src="/25.jpeg">

<img src="/26.jpeg">

___________

## __学习资料__

### <a href="https://www.bilibili.com/video/BV19J411j7SZ/?from=search&seid=1570767978370783511&spm_id_from=333.337.0.0&vd_source=f3016e32f427da115e119cd70c20b6ec" target="_blank">点击进入git学习链接连接</a>

### <a href="https://www.bilibili.com/video/BV1x64y117PX/?spm_id_from=333.337.header_right.fav_list.click&vd_source=f3016e32f427da115e119cd70c20b6ec" target="_blank">点击进入hugo学习链接</a>

### <a href="https://note.youdao.com/ynoteshare/index.html?id=7e394ebd269d0caa871fc398854fbe81&type=note&_time=1670586649015" target="_blank">点击进入Linux系统学习链接</a>

