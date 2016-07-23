---
title: Document Center
---


The documentation isn't particularly clear on this, but given that the Markdown rendering is done by Jekyll, I believe you need what they call "YAML front matter" for it to compile the page. So try putting this at the top of your file:

---
title: Document Center
---
That should be enough to trigger Jekyll. (And then you can get fancy and start using layouts, etc.)

http://stackoverflow.com/questions/15124547/can-i-use-a-markdown-file-in-a-github-page

#个人信息
姓名/性别/年龄
学历/学校以及专业
手机
邮箱
微博/个人主页
Github地址
求职意向(可选)
薪资范围(可选)
自我评价。

#个人经历
在校情况， 工作经历
按照时间优先的顺序，描述经历。尽量描述之前工作的重点、难点和亮点的项目来描述

##Task
- Situation & Task。
由于业务迭代速度加快，垂直搜索业务的性能衰减至 x 秒，性能优化刻不容缓。

- Action。
团队一共 x 人，由我发起并推动前端性能优化，其中后端研发也一起参与。
技术上主要负责前期性能监控的打点与后期评估，前端性能方案调研以及选型。
其中，性能监控在 Chrome 等浏览器下使用了 HTML5 navigation timing 得到了更为精确的性能指标数据。
调研并实现了 bigpipe 与 bigrender 技术。

- Result。
优化结果前端性能由 x 秒到 x 秒，性能直观感受提升 x0%，页面核心指标 UV/PV 提升 x0%。
除此之外，还设计了性能整改涉及的模块业务的灰度上线方案，提升了上线安全。
整体项目的结果明显，得到了经理与同事们的一致好评。

e.g.
2006年，我参与了手机XX网发布系统WAPCMS的开发（这部分是大家都会写的）。作为核心程序员，我不但完成了网站界面、调度队列的开发工作，更提出了高效的组件级缓存系统，通过碎片化缓冲有效的提升了系统的渲染效率。（这部分是很多同学忘掉的，要写出你在这个项目中具体负责的部分，以及你贡献出来的价值。）在该系统上线后，Web前端性能从10QPS提升到200QPS，服务器由10台减少到3台（通过量化的数字来增强可信度）。2008年我升任WAPCMS项目负责人，带领一个3人小组支持着每天超过2亿的PV（这就是Benefit。你能带给前雇主的价值，也就是你能带给新雇主的价值。）。

项目时间： 1x 年 01 月 - 1x 年 12 月
项目简介： 针对垂直搜索结果性能优化
职责业绩：
- Situation & Task。
由于业务迭代速度加快，垂直搜索业务的性能衰减至 x 秒，性能优化刻不容缓。

- Action。
团队一共 x 人，由我发起并推动前端性能优化，其中后端研发也一起参与。
技术上主要负责前期性能监控的打点与后期评估，前端性能方案调研以及选型。
其中，性能监控在 Chrome 等浏览器下使用了 HTML5 navigation timing 得到了更为精确的性能指标数据。
调研并实现了 bigpipe 与 bigrender 技术。

- Result。
优化结果前端性能由 x 秒到 x 秒，性能直观感受提升 x0%，页面核心指标 UV/PV 提升 x0%。
除此之外，还设计了性能整改涉及的模块业务的灰度上线方案，提升了上线安全。
整体项目的结果明显，得到了经理与同事们的一致好评。

#业余爱好和作品

开源项目，初版的书籍

#技能
#致谢
#reference
* https://leohxj.gitbooks.io/a-programmer-prepares/content/offer/about-resume.html
* http://jshe.deercv.com
* https://github.com/geekcompany/ResumeSample/blob/master/c.md

