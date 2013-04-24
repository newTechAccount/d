---
layout: post
title: "在CentOS安装ruby"
description: 
category: Ruby
tags: [CentOS, Ruby, rubygems]
---




+下载
    wget ftp://ftp.ruby-lang.org/pub/ruby/2.0/ruby-2.0.0-p0.tar.gz
    wget http://production.cf.rubygems.org/rubygems/rubygems-2.0.3.tgz    

+解压安装
    tar zxvf ruby-2.0.0-p0.tar.gz
    cd ruby-2.0.0-p0
    ./configure
    make
    make install

+安装rubygems
    tar zxvf rubygems-2.0.3.tgz
    cd rubygems-2.0.3
    ruby setup.rb
    
