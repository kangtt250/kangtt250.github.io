#The official blog for Seon Zhu. 

wechat: seonzhu

##Deploy step
###STEP1: 从仓库拉取最新代码

`git pull`

###STEP2: 将本地修改全部添加到暂存库

`git add .`

###STEP3: 添加评论并提交

`git commit -m "add"`

###STEP4: 本地预先部署jekyll主题

`gem build jekyll-theme-hydejack.gemspec`

###STEP5: 推送到rubygems

`gem push jekyll-theme-hydejack-*.gem`

Pushing gem to https://rubygems.org...

* enter email
* enter password

###STEP6: push到github，等待deployment

`git push -u origin main`

