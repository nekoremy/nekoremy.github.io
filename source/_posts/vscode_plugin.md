---
title: 个人常用 vscode 插件及配置记录
date:
categories: 开发工具
cover: https://img.vim-cn.com/4c/934f740f7660b7b7fb7b177bedf788413def4d.jpg
tags:

    - vscode

---

本文主要内容是我的 vscode 插件及配置的记录，无任何含金量。这篇博文主要是为了我今后重装系统后可以尽快恢复 vscode 环境而准备的。喜欢的可以参考一下喵

## Chinese (Simplified) Language Pack for Visual Studio Code ##

中文语言包插件，不解释

## Horizon Theme ##

![0-1](https://img.vim-cn.com/52/fb71d589d3e9d6e24ba6ef44423b7b6ed2c3c8.png)

一个我比较喜欢的编辑器主题

## Material Icon Theme ##

![0-2](https://img.vim-cn.com/e1/5cdfd54abb142453f151072231e9f9c23feb3d.png)

一个我比较喜欢的图标主题

## markdownlint ##

用于检查 Markdown 代码是否符合规范，有利于防止语法错误与维持代码风格的统一

## [markdown-formatter](https://github.com/sumnow/markdown-formatter/blob/master/README_CN.md) ##

一个可以提高 Markdown 写作效率的工具

## 用于编辑 Markdown 的配置 ##

``` json
    "[markdown]": {
        // 自动保存
        "editor.formatOnSave": true,
        // 显示空格
        "editor.renderWhitespace": "all",
        // 快速补全
        "editor.quickSuggestions": {
            "other": true,
            "comments": true,
            "strings": true
        },
        "editor.snippetSuggestions": "top",
        "editor.tabCompletion": "on",
        "editor.acceptSuggestionOnEnter": "on",
        "editor.defaultFormatter": "mervin.markdown-formatter"
    },
        "markdownFormatter.codeAreaToBlock": "",
        "markdownFormatter.fullWidthTurnHalfWidth": "auto",
        "markdownFormatter.formatOpt": {
            "indent_size": 2
        },
        "explorer.confirmDelete": false
```
