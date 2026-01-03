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
- Scoopforge/Extras-CN
- Calinou/scoop-games
- ScoopInstaller/Java
- ScoopInstaller/Versions
- arch3rPro/PST-Bucket
- hoilc/scoop-lemon
- borger/scoop-galaxy-integrations
- TheCjw/scoop-retools
- kodybrown/scoop-nirsoft
- ScoopInstaller/Nirsoft
- TheRandomLabs/scoop-nonportable
- littleli/scoop-clojure
- scoopcn/scoopcn
- ScoopInstaller/Nonportable
- tldro/scoop-security
- rasa/scoops
- Paxxs/Cluttered-bucket
- kidonng/sushi
- ACooper81/scoop-apps
- KNOXDEV/wsl
- cderv/r-bucket
- echoiron/echo-scoop
- ScoopInstaller/PHP
- hermanjustnu/scoop-emulators
- dodorz/scoop
- couleur-tweak-tips/utils
- niheaven/scoop-sysinternals
- borger/scoop-emulators
- ViCrack/scoop-bucket
- akirco/aki-apps
- wangzq/scoop-bucket
- kiennq/scoop-misc
- everyx/scoop-bucket
- Qv2ray/mochi
- cmontage/scoopbucket-third
- xrgzs/sdoog
- TheRandomLabs/Scoop-Bucket
- DoveBoy/Apps
- zhoujin7/tomato
- wzv5/ScoopBucket
- charmbracelet/scoop-bucket
- TheRandomLabs/Scoop-Python
- amorphobia/siku
- hu3rror/scoop-muggle
- jonz94/scoop-sarasa-nerd-fonts
- NyaMisty/scoopbucketmisty
- naderi/scoop-bucket
- noql-net/scoop
- kengwang/scoop-ctftools-bucket
- WinApps-share/WinApps-bucket
- ygguorun/scoop-bucket
- aliesbelik/poldi
- asimov-platform/scoop-bucket
- SayCV/scoop-cvp
- batkiz/backit
- ChungZH/peach
- AStupidBear/scoop-bear
- brian6932/dank-scoop
- Velgus/Scoop-Portapps
- Small-Ku/turbo-bucket
- Darkatse/Scoop-Darkatse
- TianXiaTech/scoop-txt
- 42wim/scoop-bucket
- starise/Scoop-Confetti
- iquiw/scoop-bucket
- Weidows-projects/scoop-3rd
- seumsc/scoop-seu
- mogeko/scoop-sysinternals
- aoisummer/scoop-bucket
- Scoopforge/Extras-Plus
- babo4d/scoop-xrtools
- jfut/scoop-jfut
- starise/Scoop-Gaming
- mo-san/scoop-bucket
- krproject/qi-windows
- rivy/scoop-bucket
- excitoon/scoop-user
- alextwothousand/scoop-bucket
- AkariiinMKII/Scoop4kariiin
- Toddli468/Pentest-Scoop-Bucket
- cc713/ownscoop
- KnotUntied/scoop-fonts
- jingyu9575/scoop-jingyu9575
- HUMORCE/nuke
- Deide/deide-bucket
- MCOfficer/scoop-bucket
- littleli/Scoop-littleli
- natecohen/scoop-av
- littleli/Scoop-AtariEmulators
- typst-community/scoop-bucket
- beer-psi/scoop-bucket
- yuusakuri/scoop-bucket
- ChinLong/scoop-customize
- Darkatse/Scoop-KanColle
