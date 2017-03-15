# opsweb
一套自己用python开发的运维综合管理平台（flask框架+cmdb+scheduler+salt)，已经成功在百合网运行2年有余,该项目还在持续不断的优化和维护并不断的新增功能。基本能够实现日常运维80%以上的重复工作，极大的提高了运维的工作效率，降低的工作强度.
主要实现功能如下：
  1.代码上线，包含测外、上线、灰度、回滚等功能并实时显示执行过程
  2.生产环境包含php、nginx、jobss，项目环境及负载均衡配置一键部署
  3.项目下线一键完成
  4.redis慢查询、数据库表查询、应用部署查询、服务器资源查询
  5.资源汇总包含mysql、redis、kafka、kestrel等基础信息
  6.实时大数据分析包含各个线上业务的并发量、流量、响应时间、业务访问占比、用户地区分布
  7.新服务器系统一键初始化
  8.cdn、ats刷新缓存、redis数据查询及删除、dns增删改查等一键完成
  9.vpn、svn、git等账号一键开通或关闭并自动发送通知邮件
  10.mysql的语句执行、审查、定时执行、进程管理一键操作
  11.运维审查包括上线操作、申请记录、日志记录
  12.访问限速、访问黑名单、用户单点登录限制等安全措施
  ver.2.3.2
  13.页面级别用户权限控制
  14.通过分布式全局锁,进程排它锁,实现多机多进程部署后台单任务运行。
