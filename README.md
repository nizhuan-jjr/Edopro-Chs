# Edopro-Chs
Chinese simplified localization pack for Edopro（Edopro简中汉化包）
## How to use/使用说明
Place **Chs** into **config\languages**

把 **Chs** 放入 **config\languages**目录下即可
## Association/关联性说明
strings.conf --> strings.conf

cards.cdb --> cards.cdb

cards-unofficial.cdb --> cards-unofficial.cdb

cards-skills.cdb --> cards-skills.cdb+cards-skills-unofficial.cdb

rush.cdb --> cards-rush.cdb

prerelease.cdb --> some prerelease cdbs under **repositories\delta-puppet**

---
strings.conf对应strings.conf

cards.cdb对应cards.cdb

cards-unofficial.cdb对应cards-unofficial.cdb

cards-skills.cdb对应cards-skills.cdb+cards-skills-unofficial.cdb

rush.cdb对应cards-rush.cdb

prerelease.cdb对应**repositories\delta-puppet**里某些prerelease的cdb
## 汉化思路
对比ygopro的cards.cdb和edopro的cards.cdb，通过DB Browser for SQLite这样的SQLite数据库工具，用edopro的setcode、脚本提示文字这样的和脚本代码结构差异有关的内容修改掉ygopro的cards.cdb的对应栏目即可。
strings.conf的话就需要用edopro的原生strings.conf结合ygopro的strings.conf内的叫法来一行行翻译了。
