---
layout: post
title: "Sinatra初试"
description: 
category: Ruby
tags: [Sinatra]
---


尝试了下Sinatra，主要参考
>http://www.sinatrarb.com/intro.html
一开始还比较顺利，后来访问的时候出了点困惑。

+安装
    gem install sinatra

+然后就是跑示例程序了
    ruby myapp.rb

到目前为止都还比较顺利，程序也跑起来了。这个时候在另外一台机器访问，提示无法访问。
后来查到这里：
>http://stackoverflow.com/questions/15685528/cannot-access-local-sinatra-server-from-another-computer-on-same-network/15689564#15689564

运行时修改为：
      ruby myapp.rb -o 0.0.0.0 -e production

搞定。
