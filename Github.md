### Terminal session recorder

<a href="https://github.com/asciinema/asciinema
">asciinema</a>: 一个用Python开发的,可以用于记录终端操作的库,说白了就是录屏...

1. 首先需要安装python的运行环境,这个网上一大堆...

2. 其次,安装该工具库

    sudo pip3 install asciinema

3. 开始录制,打开终端运行:

    asciinema rec first.cast

4. 播放录制:

    asciinema play first.cast

5. 倍数播放:

    assciinema play -s 2 frist.cast

6. 上传到服务器,这样会生成一个随机的网址,可以插入到自己的网站中,供使用.

    assciinema upload frist.cast

7. 这种相当于是提供一个链接,其实还是很不错的.

### 

