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
- hoilc/scoop-lemon
- arch3rPro/PST-Bucket
- borger/scoop-galaxy-integrations
- TheCjw/scoop-retools
- ScoopInstaller/Nirsoft
- kodybrown/scoop-nirsoft
- TheRandomLabs/scoop-nonportable
- littleli/scoop-clojure
- scoopcn/scoopcn
- ScoopInstaller/Nonportable
- tldrw/scoop-security
- rasa/scoops
- Paxxs/Cluttered-bucket
- kidonng/sushi
- ACooper81/scoop-apps
- cderv/r-bucket
- KNOXDEV/wsl
- echoiron/echo-scoop
- ScoopInstaller/PHP
- dodorz/scoop
- hermanjustnu/scoop-emulators
- niheaven/scoop-sysinternals
- couleur-tweak-tips/utils
- borger/scoop-emulators
- kiennq/scoop-misc
- xrgzs/sdoog
- ViCrack/scoop-bucket
- wangzq/scoop-bucket
- cmontage/scoopbucket-third
- akirco/aki-apps
- TheRandomLabs/Scoop-Bucket
- charmbracelet/scoop-bucket
- everyx/scoop-bucket
- Qv2ray/mochi
- DoveBoy/Apps
- EFLKumo/jam
- zhoujin7/tomato
- hu3rror/scoop-muggle
- wzv5/ScoopBucket
- TheRandomLabs/Scoop-Python
- naderi/scoop-bucket
- amorphobia/siku
- jonz94/scoop-sarasa-nerd-fonts
- NyaMisty/scoopbucketmisty
- Small-Ku/turbo-bucket
- WinApps-share/WinApps-bucket
- kengwang/scoop-ctftools-bucket
- noql-net/scoop
- ygguorun/scoop-bucket
- brian6932/dank-scoop
- Scoopforge/Extras-Plus
- aliesbelik/poldi
- Velgus/Scoop-Portapps
- asimov-platform/scoop-bucket
- SayCV/scoop-cvp
- batkiz/backit
- zirnc/peach
- AStupidBear/scoop-bear
- Weidows-projects/scoop-3rd
- Darkatse/Scoop-Darkatse
- TianXiaTech/scoop-txt
- 42wim/scoop-bucket
- iquiw/scoop-bucket
- starise/Scoop-Confetti
- seumsc/scoop-seu
- ocodo/wezterm-alt-windows-icon-builds
- mogeko/scoop-sysinternals
- starise/Scoop-Gaming
- mo-san/scoop-bucket
- babo4d/scoop-xrtools
- jfut/scoop-jfut
- AkariiinMKII/Scoop4kariiin
- aoisummer/scoop-bucket
- krproject/qi-windows
- rivy/scoop-bucket
- excitoon/scoop-user
- alextwothousand/scoop-bucket
- Toddli468/Pentest-Scoop-Bucket
- cc713/ownscoop
- natecohen/scoop-av
- typst-community/scoop-bucket
- KnotUntied/scoop-fonts
- 404NetworkError/scoop-bucket
- jingyu9575/scoop-jingyu9575
- BenjaminMichaelis/Config
- p8rdev/scoop-portableapps
- AntonOks/scoop-aoks
- Deide/deide-bucket
- HUMORCE/nuke
- MCOfficer/scoop-bucket
- littleli/Scoop-littleli
- maboloshi/scoop-private
- littleli/Scoop-AtariEmulators
- beer-psi/scoop-bucket
- yuusakuri/scoop-bucket
- ChinLong/scoop-customize
- Darkatse/Scoop-KanColle
