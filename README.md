<p align="center">
	<a href="https://gitmoji.carloscuesta.me">
		<img src="https://cloud.githubusercontent.com/assets/7629661/20073135/4e3db2c2-a52b-11e6-85e1-661a8212045a.gif" width="456" alt="gitmoji">
	</a>
</p>
<p align="center">
	<a href="https://travis-ci.org/carloscuesta/gitmoji">
		<img src="https://img.shields.io/travis/carloscuesta/gitmoji.svg?style=flat-square"
			 alt="Build Status">
	</a>
	<a href="https://gitmoji.carloscuesta.me">
		<img src="https://img.shields.io/badge/gitmoji-%20😜%20😍-FFDD67.svg?style=flat-square"
			 alt="Gitmoji">
	</a>
</p>


# git emoji
==================

Introduction
-----
Git提供了emoj的功能，在一条commit信息的开头加上各种各样的emoji可以清楚的了解到该commit的主要改动类型

Format
-----
Git Emoji Commit 格式:
```
:emoji1: :emoji2: Subject
(Only One NewLine)
Message Body
(Only One NewLine)
Ref <###>
```

Emojis
----------------

| Emoji | 语法 | 适用场景 |
|:---:|:---:|---|
| **修改类** |
| :bug: | `:bug:` | 报告bug，[`@FIXME`](https://github.com/slashsBin/styleguide-todo-grammar#bug-report) |
| :ambulance: | `:ambulance:` | 处理bug |
| :art: | `:art:` | 改进代码格式或代码结构 |
| :fire: | `:fire:` | 移除代码或文件， `@CHANGED` Comment Tag |
| :checkered_flag: | `:checkered_flag:` | 处理**Windows**上的问题 |
| :penguin: | `:penguin:` | 处理**Linux**上的问题 |
| :apple: | `:apple:` | 处理**Mac OS**上的问题|
| :lipstick: | `:lipstick:` | 改进**UI**界面或者样式文件 |
| :wheelchair: | `:wheelchair:` | 修改权限 |
| :construction: | `:construction:` | 工作进行中，`@REVIEW` Comment Tag |
|**性能类**|
| :racehorse: | `:racehorse:` | 提升**性能** |
| :arrow_up: | `:arrow_up:` | 升级依赖 |
| :arrow_down: | `:arrow_down:` | 降级依赖 |
|**配置类**|
| :snowflake: | `:snowflake:` | 更改配置文件, 一般组合使用的emoji :penguin:、:ribbon:、:rocket: |
| :ribbon: | `:ribbon:` | 客户端请求的应用程序，`@HACK` Comment Tag |
|**部署类**|
| :rocket: | `:rocket:` | 跟部署有关的任何事 |
| :gem: | `:gem:` | New **Release**，新的发布 |
| :bookmark: | `:bookmark:` | 版本标签 |
| :speaker: | `:speaker:` | 增加日志记录 |
| :mute: | `:mute:` | 减少日志记录 |
| :green_heart: | `:green_heart:` | **CI** 构建 |
|**数据库**|
| :dolphin: | `:dolphin:` | **MySQL** 数据库的相关操作 |
| :elephant: | `:elephant:` | **PostgreSQL** 数据库的相关操作 |
|**增加类**|
| :sparkles: | `:sparkles:` | **New** Features，增加**新功能**|
| :bulb: | `:bulb:` |**新概念**， `@IDEA` Comment Tag |
| :zap: | `:zap:` | 引入**不向后兼容**的特性， `@CHANGED` Comment Tag |
|**其他类**|
| :books: | `:books:` | 书写**文档** |
| :lock: | `:lock:` | 处理**安全**问题 |
| :shirt: | `:shirt:` | 删除简短、严格或者弃用等类型的警告 |
| :tada: | `:tada:` | 第一次commit |
| :white_check_mark: | `:white_check_mark:` | 增加测试 |

