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
- Calinou/scoop-games
- ScoopInstaller/Java
- ivaquero/scoopet
- ScoopInstaller/Versions
- borger/scoop-galaxy-integrations
- TheCjw/scoop-retools
- TheRandomLabs/scoop-nonportable
- kodybrown/scoop-nirsoft
- littleli/scoop-clojure
- arch3rPro/PST-Bucket
- hoilc/scoop-lemon
- ScoopInstaller/Nirsoft
- scoopcn/scoopcn
- rasa/scoops
- kidonng/sushi
- Paxxs/Cluttered-bucket
- ScoopInstaller/Nonportable
- KNOXDEV/wsl
- echoiron/echo-scoop
- ACooper81/scoop-apps
- cderv/r-bucket
- couleur-tweak-tips/utils
- hermanjustnu/scoop-emulators
- dodorz/scoop
- everyx/scoop-bucket
- borger/scoop-emulators
- Qv2ray/mochi
- kiennq/scoop-misc
- TheRandomLabs/Scoop-Bucket
- ViCrack/scoop-bucket
- wangzq/scoop-bucket
- niheaven/scoop-sysinternals
- akirco/aki-apps
- wzv5/ScoopBucket
- zhoujin7/tomato
- TheRandomLabs/Scoop-Python
- DoveBoy/Apps
- whoopscs/scoop-security
- jonz94/scoop-sarasa-nerd-fonts
- amorphobia/siku
- naderi/scoop-bucket
- charmbracelet/scoop-bucket
- hu3rror/scoop-muggle
- NyaMisty/scoopbucketmisty
- ygguorun/scoop-bucket
- noql-net/scoop
- batkiz/backit
- ChungZH/peach
- 42wim/scoop-bucket
- AStupidBear/scoop-bear
- iquiw/scoop-bucket
- mogeko/scoop-sysinternals
- Velgus/Scoop-Portapps
- brian6932/dank-scoop
- jfut/scoop-jfut
- SayCV/scoop-cvp
- cc713/ownscoop
- aoisummer/scoop-bucket
- aliesbelik/poldi
- krproject/qi-windows
- rivy/scoop-bucket
- excitoon/scoop-user
- Darkatse/Scoop-Darkatse
- TianXiaTech/scoop-txt
- alextwothousand/scoop-bucket
- Weidows-projects/scoop-3rd
- littleli/Scoop-littleli
- AkariiinMKII/Scoop4kariiin
- starise/Scoop-Confetti
- seumsc/scoop-seu
- HUMORCE/nuke
- Toddli468/Pentest-Scoop-Bucket
- mo-san/scoop-bucket
- beer-psi/scoop-bucket
- yuusakuri/scoop-bucket
- ChinLong/scoop-customize
- Darkatse/Scoop-KanColle
