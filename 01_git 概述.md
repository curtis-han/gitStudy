# git 概述

## git结构

git是两重结构管理，本地库和远程库。

### git本地结构

![local](/Users/curtis/github/gitstudy/resource/local.jpg)

**工作区** 就是普通的文件，不受git版本控制，比如在本地工作中新建和修改的文件。

**缓存区** 临时保存区，毕竟有些文件虽然新建和修改，但是不想让它commit本地的git版本管理中。

**本地区** 已经是确定的东西，完全进入git的版本管理的文件。