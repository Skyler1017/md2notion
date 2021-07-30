<p align="center">
    <a href="https://github.com/Cobertos/md2notion/actions" target="_blank"><img alt="build status" src="https://github.com/Cobertos/md2notion/workflows/Package%20Tests/badge.svg"></a>
    <a href="https://pypi.org/project/md2notion/" target="_blank"><img alt="pypi python versions" src="https://img.shields.io/pypi/pyversions/md2notion.svg"></a>
    <a href="https://twitter.com/cobertos" target="_blank"><img alt="twitter" src="https://img.shields.io/badge/twitter-%40cobertos-0084b4.svg"></a>
    <a href="https://cobertos.com" target="_blank"><img alt="twitter" src="https://img.shields.io/badge/website-cobertos.com-888888.svg"></a>
</p>

# 迁移markdown文件到 Notion

将一个文件夹的所有`.md`文件按文件夹结构迁移到 notion，保留代码高亮(c python go)

## 使用方法
1. 在notion中创建一个页面，复制链接（右上角 copy link）
2. 打开 [notion 网页版](notion.so) 链接,进入开发者模式，打开cookie，复制下 token_v2 字段
3. 复制 markdown文件夹的绝对路径，如 /Users/you/md-folder
4. 运行下面的命令：
```
git clone https://github.com/Skyler1017/md2notion.git
cd md2notion/md2notion
python3 __main__.py  [token_v2] [page_url] [/Users/you/md-folder]
```

## 迁移效果

![-w334](https://image-1300159044.cos.ap-hongkong.myqcloud.com/mweb/2021/07/30/16276392628374.jpg)
![-w316](https://image-1300159044.cos.ap-hongkong.myqcloud.com/mweb/2021/07/30/16276392963447.jpg)