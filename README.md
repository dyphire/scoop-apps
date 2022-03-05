# 仓库说明

- 合并多个scoop仓库，仅克隆最新的一个版本
- 自动处理同名文件,仓库靠前优先使用，其他仓库同名文件按"软件-贡献人ID"进行重命名
- 每天自动更新
- 未对仓库软件来源进行安全检验，请自行甄别恶意软件，或者使用杀毒软件
- 此仓库为合并仓库，不接受Pull requests，请参考仓库根路径的app-contributor-list.txt到相应的仓库提交pull requests
- 目前仓库根据scoop-directory自动添加其他scoop仓库，规则是软件数量大于10并且star数据大于5的仓库。不接受仓库推荐以及不维护仓库清理等相关Issues
- 名称歧义修正功能
- 同名文件md5去重
- 合并仓库的scripts文件夹
- 根据Github项目[scoop-directory](https://github.com/rasa/scoop-directory)动态生成bucket.config，[前端地址](https://rasa.github.io/scoop-directory/)
- 如果是国内的网络环境，可以使用https://gitee.com/kkzzhizhou/scoop-apps

# 仓库重置说明

因之前版本每小时提交commit,累计有8000+个commit,绝大部分已经属于无用的信息，因此重置本仓库为最新一次的提交，并修改仓库为每天更新两次。

恢复使用本仓库的方式

```
scoop bucket rm apps
scoop bucket add apps https://github.com/kkzzhizhou/scoop-apps
# 国内网络
scoop bucket add apps https://gitee.com/kkzzhizhou/scoop-apps
```

# 合并仓库列表

- kkzzhizhou/scoop-zapps
- ScoopInstaller/Extras
- chawyehsu/dorado
- matthewjberger/scoop-nerd-fonts
- ScoopInstaller/Java
- Calinou/scoop-games
- TheRandomLabs/scoop-nonportable
- borger/scoop-galaxy-integrations
- TheCjw/scoop-retools
- ivaquero/scoopet
- ScoopInstaller/Versions
- kodybrown/scoop-nirsoft
- Ash258/Scoop-JetBrains
- littleli/scoop-clojure
- L-Trump/scoop-raresoft
- kidonng/sushi
- rasa/scoops
- MCOfficer/scoop-nirsoft
- hermanjustnu/scoop-emulators
- KNOXDEV/wsl
- everyx/scoop-bucket
- echoiron/echo-scoop
- TheRandomLabs/Scoop-Bucket
- cderv/r-bucket
- Qv2ray/mochi
- dodorz/scoop
- wangzq/scoop-bucket
- zhoujin7/tomato
- ZvonimirSun/scoop-iszy
- kiennq/scoop-misc
- scoopcn/scoopcn
- hoilc/scoop-lemon
- borger/scoop-emulators
- Paxxs/Cluttered-bucket
- wzv5/ScoopBucket
- TheRandomLabs/Scoop-Python
- ChungZH/peach
- AStupidBear/scoop-bear
- Ryanjiena/scoop-apps
- ACooper81/scoop-apps
- excitoon/scoop-user
- naderi/scoop-bucket
- iquiw/scoop-bucket
- 42wim/scoop-bucket
- batkiz/backit
- Velgus/Scoop-Portapps
- Darkatse/Scoop-Darkatse
- liaoya/scoop-bucket
- jfut/scoop-jfut
- krproject/qi-windows
- ChinLong/scoop-customize
- Apocalypsor/My-Scoop-Bucket
