## 二进制包安装
- 框架无版本要求，通过本仓库下载最新agetserver的tgz包
- 在TarsWeb部署一个Alarm.AgentServer应用，服务类型tarscpp，**模板tars-framework-db**
- 新建一个服务配置AgentServer.conf，拷贝复制目录同名配置文件的内容，填入购买的**环境标识**
- 部署成功后，如普通应用一样上传并发布AgentServer即可，如果TarsWeb的Notify面板没有异常提示即为启动成功，可在告警Web确认节点是否正常接入
- 注意agentserver所在服务器必须要能访问外网

## v1.0.1 20220905
- feat：适配协议，被频控的历史只由Agent上报
- feat：优化频控策略，更符合正常理解
- feat：Agent与云后端的错误，Notify到用户TarsWeb

## v1.0.0 20220823
- 完成第一个版本
 


