最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Hands‑on：简易短链接服务完整开发实践
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.ecn2dy.asia/arts/462551.Doc

原标题：golang 系统设计内部服务链路 trace 传递实现
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.ecn2dy.asia/arts/925871.Doc

原标题：golang 系统设计数据库死锁分析规避
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.ecn2dy.asia/arts/961628.Doc

原标题：golang redis 发布订阅简单示例
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.ecn2dy.asia/arts/486571.Doc

原标题：golang redis 发布订阅简单示例
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.ecn2dy.asia/arts/896774.Doc

原标题：WebSocket 双向通信 demo 开发
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://wiki.ecn2dy.asia/arts/759147.Doc

原标题：golang 系统设计 pre‑commit 钩子本地代码校验
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://wiki.ecn2dy.asia/arts/282400.Doc

原标题：golang 系统设计数据库死锁分析规避
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.ecn2dy.asia/arts/159587.Doc

原标题：golang html 模板渲染简单示例
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://wiki.ecn2dy.asia/arts/570060.Doc

原标题：golang 系统设计多租户数据隔离方案
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://wiki.ecn2dy.asia/arts/679149.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.ecn2dy.asia/arts/538770.Doc

原标题：golang grafana 监控面板简单配置
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.ecn2dy.asia/arts/527674.Doc

原标题：性能复盘：内存泄漏定位，内存持续上涨优化
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.ecn2dy.asia/arts/824906.Doc

原标题：golang mysql 死锁排查步骤讲解
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.ecn2dy.asia/arts/596558.Doc

原标题：golang 系统设计大流量削峰处理方案
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://wiki.ecn2dy.asia/arts/066218.Doc

原标题：架构笔记：数据脱敏架构接入层与存储层方案
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://wiki.ecn2dy.asia/arts/574366.Doc

原标题：前端图片懒加载性能优化
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://wiki.ecn2dy.asia/arts/156966.Doc

原标题：项目实践：定时任务防重复执行落地实践
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.ecn2dy.asia/arts/523521.Doc

原标题：golang 系统设计熔断算法 hystrix 思路
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.ecn2dy.asia/arts/852114.Doc

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.ecn2dy.asia/arts/647325.Doc

原标题：Performance：数据库分表解决单表过大性能衰减
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://wiki.ecn2dy.asia/arts/944035.Doc

原标题：Docker Compose 一键搭建本地栈
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.ecn2dy.asia/arts/238880.Doc

原标题：golang 熔断降级简易组件开发
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.ecn2dy.asia/arts/239333.Doc

原标题：WSL 搭建 Windows Linux 开发环境
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.ecn2dy.asia/arts/711550.Doc

原标题：数据库分表存储大表优化方案
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.ecn2dy.asia/arts/769000.Doc

原标题：golang 系统设计开源版本发布 changelog 维护
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.ecn2dy.asia/arts/356965.Doc

原标题：Git 分支切换合并删除完整操作
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.ecn2dy.asia/arts/459805.Doc

原标题：设计思考：消息队列重复消费架构层防御手段
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://wiki.ecn2dy.asia/arts/759552.Doc

原标题：golang minio 分片上传断点续传
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.ecn2dy.asia/arts/719130.Doc

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.ecn2dy.asia/arts/686591.Doc

原标题：安全复盘：Redis命令注入风险防护手段
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://wiki.ecn2dy.asia/arts/947987.Doc

原标题：golang 系统设计雪花算法 id 原理剖析
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://wiki.ecn2dy.asia/arts/186513.Doc

原标题：golang 系统设计数据库查询优化完整流程
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.ecn2dy.asia/arts/541289.Doc

原标题：golang 速率限制令牌桶实现
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.ecn2dy.asia/arts/204049.Doc

原标题：快速上手简单的限流逻辑模拟实现
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://wiki.ecn2dy.asia/arts/411072.Doc

原标题：坑点：gitsubmodule子模块更新失败踩坑
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://wiki.ecn2dy.asia/arts/618660.Doc

原标题：golang 系统设计传输加密 tls 配置要点
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://wiki.ecn2dy.asia/arts/082705.Doc

原标题：JSON XML 数据解析处理示例
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://wiki.ecn2dy.asia/arts/245626.Doc

原标题：DNS 解析异常第三方调用故障
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://wiki.ecn2dy.asia/arts/123916.Doc

原标题：golang grafana 面板变量模板制作
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://wiki.ecn2dy.asia/arts/018479.Doc


二、踩坑排错｜Troubleshooting
原标题：安全实践：敏感信息加密存储传输完整方案
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.ecn2dy.asia/arts/188347.Doc

原标题：golang 系统设计分布式事务业务选型决策思路
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.ecn2dy.asia/arts/146161.Doc

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.ecn2dy.asia/arts/466846.Doc

原标题：Hands‑on：简易跨进程通信demo开发实践
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://wiki.ecn2dy.asia/arts/651982.Doc

原标题：golang 系统设计降级策略开关配置方案
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.ecn2dy.asia/arts/855599.Doc

原标题：golang k8s 滚动更新回滚策略
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://wiki.ecn2dy.asia/arts/184100.Doc

原标题：程序信号中断退出处理逻辑
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.ecn2dy.asia/arts/156436.Doc

原标题：golang redis 分布式计数器开发
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://wiki.ecn2dy.asia/arts/673629.Doc

原标题：golang 系统设计数据库慢请求排查流程
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://wiki.ecn2dy.asia/arts/938511.Doc

原标题：golang goroutine 协程基础实操
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://wiki.ecn2dy.asia/arts/193726.Doc

原标题：布隆过滤器误判问题修正
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://wiki.ecn2dy.asia/arts/590307.Doc

原标题：安全实践：请求输入校验防御恶意参数
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://wiki.ecn2dy.asia/arts/821181.Doc

原标题：慢查询分析索引调优数据库实战
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://wiki.ecn2dy.asia/arts/751863.Doc

原标题：Architecture：安全防护架构XSSCSRFSQL注入防御
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://wiki.ecn2dy.asia/arts/677933.Doc

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.ecn2dy.asia/arts/247759.Doc

原标题：golang 系统设计缓存优化落地实操指南
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.ecn2dy.asia/arts/344777.Doc

原标题：开源实践：给开源项目写单元测试贡献代码
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://wiki.ecn2dy.asia/arts/101441.Doc

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://wiki.ecn2dy.asia/arts/833829.Doc

原标题：golang docker 私有仓库搭建使用
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://wiki.ecn2dy.asia/arts/492562.Doc

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.ecn2dy.asia/arts/486643.Doc

原标题：DNS TTL 配置域名切换生效
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.ecn2dy.asia/arts/947832.Doc

原标题：Architecture：对象存储接入业务整体架构
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.ecn2dy.asia/arts/087211.Doc

原标题：golang 系统设计监控告警体系搭建思路
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://wiki.ecn2dy.asia/arts/018803.Doc

原标题：TCP 心跳检测清理僵死连接
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.ecn2dy.asia/arts/062210.Doc

原标题：golang mysql 避免 select * 查询
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.ecn2dy.asia/arts/445628.Doc

原标题：golang makefile 自动化构建脚本
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://wiki.ecn2dy.asia/arts/448844.Doc

原标题：调优方案：Docker容器内核参数性能调优
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.ecn2dy.asia/arts/600768.Doc

原标题：架构复盘：供应链安全架构依赖包风险治理
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.ecn2dy.asia/arts/866136.Doc

原标题：业务错误码体系设计方案
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.ecn2dy.asia/arts/377438.Doc

原标题：golang docker 多阶段构建 go 镜像
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://wiki.ecn2dy.asia/arts/121138.Doc

原标题：golang 系统设计内存复用 sync.pool 使用
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.ecn2dy.asia/arts/074433.Doc

原标题：实战：数据库explain执行计划分析实操演练
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://wiki.ecn2dy.asia/arts/667044.Doc

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.ecn2dy.asia/arts/417436.Doc

原标题：golang es 更新文档注意版本冲突
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://wiki.ecn2dy.asia/arts/612712.Doc

原标题：坑点：npm/pip全局版本与项目本地版本冲突
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.ecn2dy.asia/arts/640766.Doc

原标题：调优方案：数据库索引不要过度建立，权衡写性能
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://wiki.ecn2dy.asia/arts/159444.Doc

原标题：线上故障：第三方接口超时未设置熔断雪崩
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://wiki.ecn2dy.asia/arts/670224.Doc

原标题：golang docker 部署 mongodb 开发环境
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://wiki.ecn2dy.asia/arts/947062.Doc

原标题：移动端适配 rem vw 方案对比
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.ecn2dy.asia/arts/055835.Doc

原标题：Hands‑on：简易事件驱动架构原型开发
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://wiki.ecn2dy.asia/arts/346996.Doc

三、实战开发｜Practice
原标题：容器内存扩容 OOM 被杀死修复
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://wiki.ecn2dy.asia/arts/614428.Doc

原标题：golang 系统设计回调签名校验防伪造实现
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://wiki.ecn2dy.asia/arts/227479.Doc

原标题：golang 系统设计分表跨表 join 业务处理方案
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.ecn2dy.asia/arts/162516.Doc

原标题：golang 接口限流中间件开发
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://wiki.ecn2dy.asia/arts/457983.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://wiki.ecn2dy.asia/arts/488746.Doc

原标题：golang 系统设计 cpu 瓶颈定位优化方案
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.ecn2dy.asia/arts/101149.Doc

原标题：优化实践：接口批量合并减少网络请求次数
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://wiki.ecn2dy.asia/arts/852538.Doc

原标题：golang 系统设计故障预案编写模板参考示例
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.ecn2dy.asia/arts/907167.Doc

原标题：Architecture：BFF后端聚合层架构适用场景
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://wiki.ecn2dy.asia/arts/100832.Doc

原标题：线上故障：慢查询拖垮整个数据库服务
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://wiki.ecn2dy.asia/arts/129245.Doc

原标题：DevOps：私有镜像仓库搭建与权限管控
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.ecn2dy.asia/arts/122335.Doc

原标题：架构复盘：容器资源隔离架构CPU内存限制设计
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.ecn2dy.asia/arts/761380.Doc

原标题：golang 系统设计内部 rpc 接口设计原则梳理
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.ecn2dy.asia/arts/304409.Doc

原标题：异步编程 Promise 执行流程解析
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://wiki.ecn2dy.asia/arts/230189.Doc

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://wiki.ecn2dy.asia/arts/022442.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.ecn2dy.asia/arts/143840.Doc

原标题：异步编程 Promise 执行流程解析
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://wiki.ecn2dy.asia/arts/641805.Doc

原标题：vite 项目配置与构建提速技巧
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.ecn2dy.asia/arts/690039.Doc

原标题：架构复盘：限流系统架构防止恶意流量冲击
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.ecn2dy.asia/arts/085663.Doc

原标题：设计思考：API网关和BFF职责边界划分
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.ecn2dy.asia/arts/306091.Doc

原标题：服务健康检查告警监控体系
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.ecn2dy.asia/arts/254579.Doc

原标题：前端打包分包加载提速方案
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://wiki.ecn2dy.asia/arts/612905.Doc

原标题：golang 系统设计 api 文档 swagger redoc 落地
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.ecn2dy.asia/arts/271252.Doc

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://wiki.ecn2dy.asia/arts/488868.Doc

原标题：Mock 接口服务快速搭建实操
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://wiki.ecn2dy.asia/arts/115629.Doc

原标题：golang 系统设计架构图绘图工具选型对比
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.ecn2dy.asia/arts/277546.Doc

原标题：大文件导出内存溢出防护
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.ecn2dy.asia/arts/225541.Doc

原标题：golang 系统设计防爬虫简单策略
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.ecn2dy.asia/arts/614696.Doc

原标题：安全笔记：请求头伪造IP漏洞防护
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://wiki.ecn2dy.asia/arts/455907.Doc

原标题：nodejs 项目 pm2 部署运维指南
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.ecn2dy.asia/arts/285210.Doc

原标题：Hands‑on：简易布隆过滤器实现与测试验证
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.ecn2dy.asia/arts/785995.Doc

原标题：坑点：gitcherry‑pick引入不兼容代码
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.ecn2dy.asia/arts/059922.Doc

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://wiki.ecn2dy.asia/arts/260885.Doc

原标题：golang 系统设计令牌桶漏桶算法对比
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.ecn2dy.asia/arts/074244.Doc

原标题：nestjs 拦截器过滤器管道实战
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.ecn2dy.asia/arts/659369.Doc

原标题：hosts 配置本地回环访问修复
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.ecn2dy.asia/arts/855922.Doc

原标题：数据库读写分离性能优化
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://wiki.ecn2dy.asia/arts/744430.Doc

原标题：TLS 版本兼容 HTTPS 握手失败
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://wiki.ecn2dy.asia/arts/675914.Doc

原标题：依赖版本冲突兼容修复方案
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.ecn2dy.asia/arts/193812.Doc

原标题：入门实践：Git分支创建切换合并完整演示
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://wiki.ecn2dy.asia/arts/290477.Doc

四、架构设计｜Architecture
原标题：Hands‑on：静态资源CDN缓存控制头配置实践
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.ecn2dy.asia/arts/318463.Doc

原标题：golang 错误处理最佳实践汇总
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.ecn2dy.asia/arts/537850.Doc

原标题：AI实践：大模型生成测试用例实践与校验
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.ecn2dy.asia/arts/223738.Doc

原标题：golang 系统设计数据库慢请求排查流程
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.ecn2dy.asia/arts/332867.Doc

原标题：Hands‑on：本地模拟消息重复消费处理实践
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://wiki.ecn2dy.asia/arts/388836.Doc

原标题：golang 系统设计高可用服务架构梳理
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.ecn2dy.asia/arts/317897.Doc

原标题：golang 系统设计消息队列解耦削峰
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.ecn2dy.asia/arts/806818.Doc

原标题：golang mysql 长连接短连接对比
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://wiki.ecn2dy.asia/arts/016047.Doc

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://wiki.ecn2dy.asia/arts/605974.Doc

原标题：内网测试服务搭建团队调试
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://wiki.ecn2dy.asia/arts/802055.Doc

原标题：实战：Nginx负载均衡多种策略配置实践
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.ecn2dy.asia/arts/128366.Doc

原标题：golang 系统设计第三方接口调用封装思路
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://wiki.ecn2dy.asia/arts/751114.Doc

原标题：golang 系统设计线上故障排查完整流程
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.ecn2dy.asia/arts/010842.Doc

原标题：前端静态缓存更新生效处理
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://wiki.ecn2dy.asia/arts/674751.Doc

原标题：游标分页大数据查询性能提升
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.ecn2dy.asia/arts/422646.Doc

原标题：多套环境灵活切换配置方案
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://wiki.ecn2dy.asia/arts/447251.Doc

原标题：设计思考：消息队列重复消费架构层防御手段
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.ecn2dy.asia/arts/670115.Doc

原标题：Security：Docker镜像安全扫描漏洞修复
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://wiki.ecn2dy.asia/arts/856724.Doc

?
