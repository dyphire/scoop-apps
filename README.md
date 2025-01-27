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
- ivaquero/scoopet
- ScoopInstaller/Java
- ScoopInstaller/Versions
- borger/scoop-galaxy-integrations
- arch3rPro/PST-Bucket
- TheCjw/scoop-retools
- kodybrown/scoop-nirsoft
- TheRandomLabs/scoop-nonportable
- hoilc/scoop-lemon
- littleli/scoop-clojure
- ScoopInstaller/Nirsoft
- scoopcn/scoopcn
- rasa/scoops
- kidonng/sushi
- ScoopInstaller/Nonportable
- Paxxs/Cluttered-bucket
- KNOXDEV/wsl
- ACooper81/scoop-apps
- echoiron/echo-scoop
- cderv/r-bucket
- hermanjustnu/scoop-emulators
- couleur-tweak-tips/utils
- dodorz/scoop
- niheaven/scoop-sysinternals
- ViCrack/scoop-bucket
- whoopscs/scoop-security
- borger/scoop-emulators
- everyx/scoop-bucket
- wangzq/scoop-bucket
- Qv2ray/mochi
- TheRandomLabs/Scoop-Bucket
- kiennq/scoop-misc
- akirco/aki-apps
- zhoujin7/tomato
- wzv5/ScoopBucket
- TheRandomLabs/Scoop-Python
- DoveBoy/Apps
- charmbracelet/scoop-bucket
- jonz94/scoop-sarasa-nerd-fonts
- naderi/scoop-bucket
- amorphobia/siku
- hu3rror/scoop-muggle
- cmontage/scoopbucket-third
- NyaMisty/scoopbucketmisty
- ygguorun/scoop-bucket
- noql-net/scoop
- abgox/abgobucket
- kengwang/scoop-ctftools-bucket
- aliesbelik/poldi
- Velgus/Scoop-Portapps
- batkiz/backit
- ChungZH/peach
- 42wim/scoop-bucket
- AStupidBear/scoop-bear
- iquiw/scoop-bucket
- SayCV/scoop-cvp
- mogeko/scoop-sysinternals
- brian6932/dank-scoop
- jfut/scoop-jfut
- starise/Scoop-Gaming
- xrgzs/sdoog
- cc713/ownscoop
- starise/Scoop-Confetti
- aoisummer/scoop-bucket
- seumsc/scoop-seu
- krproject/qi-windows
- rivy/scoop-bucket
- excitoon/scoop-user
- Darkatse/Scoop-Darkatse
- TianXiaTech/scoop-txt
- alextwothousand/scoop-bucket
- Weidows-projects/scoop-3rd
- babo4d/scoop-xrtools
- Darkatse/Scoop-KanColle
- HUMORCE/nuke
- Toddli468/Pentest-Scoop-Bucket
- littleli/Scoop-littleli
- AkariiinMKII/Scoop4kariiin
- BenjaminMichaelis/Config
- mo-san/scoop-bucket
- WinApps-share/WinApps-bucket
- beer-psi/scoop-bucket
- Small-Ku/turbo-bucket
- yuusakuri/scoop-bucket
- ChinLong/scoop-customize
