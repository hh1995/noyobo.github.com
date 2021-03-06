---
layout: post
title: "gbm git分支管理工具"
description: "gbm git分支管理工具,释放你的双手,简化你的输入操作."
category: git
tags: [npm,git]
keywords: git,branch
date: 2014-10-16 14:45:30
---
gbm
===

[![Build Status](https://travis-ci.org/noyobo/gbm.svg)](https://travis-ci.org/noyobo/gbm)
[![npm version](http://img.shields.io/npm/v/gbm.svg)](https://www.npmjs.org/package/gbm)
[![npm download](http://img.shields.io/npm/dm/gbm.svg)](https://www.npmjs.org/package/gbm)

[![NPM](https://nodei.co/npm/gbm.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/gbm/)

CLI Tool `gbm` Git branch manage to package.json version daily/x.y.z

## Install

```
$ npm install -g gbm
```

## Usage


```ruby
  Usage: gbm <commands> [options]

  Commands:

    new|n [x.y.z|options]
       创建新分支

    bump|b [options]
       增加当前版本号

    commit|c <message>
       添加所有变更文件 and commit

    switch|s <x.y.z>
       切换分支到 daily/x.y.z

    set <x.y.z>
       设置当前版本号 and commit

    get
       获取当前版本号

    push|prepub
       推送当前分支到远端

    publish
       发布当前分支资源

    sync
       同步当前版本号

    up|upgrade
       检查 `gbm` 更新

  Options:

    -h, --help     output usage information
    -V, --version  output the version number
    -M, --major    主版本号增加 Eg. 1.0.2 -> 2.0.0
    -m, --minor    次版本号增加 default Eg. 1.0.2 -> 1.1.0
    -p, --patch    补丁版本号增加 Eg. 1.0.2 -> 1.0.3
```
