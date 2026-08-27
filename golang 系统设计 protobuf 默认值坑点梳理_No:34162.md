最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 protobuf 默认值坑点梳理
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://book.kdjkln.asia/blog/8939167.sHtMl

原标题：设计思考：分布式锁选型、风险、业务约束
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://book.kdjkln.asia/blog/2851417.sHtMl

原标题：全量回归测试提升代码质量
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://book.kdjkln.asia/blog/0161842.sHtMl

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://book.kdjkln.asia/blog/1193989.sHtMl

原标题：实战：GraphQL服务搭建与CRUD实操
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://book.kdjkln.asia/blog/9267895.sHtMl

原标题：golang 系统设计缓存空值防止缓存穿透实现
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://book.kdjkln.asia/blog/7867617.sHtMl

原标题：Security：接口鉴权越权漏洞检测与修复
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://book.kdjkln.asia/blog/3779917.sHtMl

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://book.kdjkln.asia/blog/1784188.sHtMl

原标题：快速上手简单信号处理脚本编写
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.kdjkln.asia/blog/1574161.sHtMl

原标题：避坑：版本升级之后项目直接无法启动
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://book.kdjkln.asia/blog/2358348.sHtMl

原标题：golang 系统设计锁优化减少竞争提升吞吐
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://book.kdjkln.asia/blog/9175045.sHtMl

原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.kdjkln.asia/blog/8019271.sHtMl

原标题：排错：打包后资源路径，开发生产行为不一致
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://book.kdjkln.asia/blog/2635617.sHtMl

原标题：请求重试组件退避策略实现
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://book.kdjkln.asia/blog/1820215.sHtMl

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://book.kdjkln.asia/blog/2329477.sHtMl

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://book.kdjkln.asia/blog/2678274.sHtMl

原标题：Performance：后端接口性能优化完整分析流程
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://book.kdjkln.asia/blog/3064329.sHtMl

原标题：新手向：项目目录结构规范与含义解析
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://book.kdjkln.asia/blog/1386317.sHtMl

原标题：golang 系统设计消息 partition 数量设置思路
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.kdjkln.asia/blog/7651708.sHtMl

原标题：golang 系统设计字符串拼接性能优化技巧
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://book.kdjkln.asia/blog/5995505.sHtMl

原标题：实战项目：实现分布式任务调度最小原型
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://book.kdjkln.asia/blog/7591679.sHtMl

原标题：golang 内存缓存简单实现方案
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://book.kdjkln.asia/blog/2300807.sHtMl

原标题：golang k8s secret 加密敏感信息
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://book.kdjkln.asia/blog/8248678.sHtMl

原标题：WebSocket 双向通信 demo 开发
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://book.kdjkln.asia/blog/7562697.sHtMl

原标题：golang 错误处理最佳实践汇总
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://book.kdjkln.asia/blog/1543715.sHtMl

原标题：golang yaml 解析配置加载实操
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://book.kdjkln.asia/blog/6379168.sHtMl

原标题：记一次字符集编码不一致乱码问题全排查
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://book.kdjkln.asia/blog/3140225.sHtMl

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://book.kdjkln.asia/blog/4822025.sHtMl

原标题：开发复盘：搭建文件上传服务支持分片断点续传
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://book.kdjkln.asia/blog/3794547.sHtMl

原标题：golang es 映射 mapping 设计避坑
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://book.kdjkln.asia/blog/1860195.sHtMl

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://book.kdjkln.asia/blog/9025893.sHtMl

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://book.kdjkln.asia/blog/1976081.sHtMl

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://book.kdjkln.asia/blog/6532981.sHtMl

原标题：golang 系统设计传输加密 tls 配置要点
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://book.kdjkln.asia/blog/3942951.sHtMl

原标题：新手教程：本地项目初始化gitignore配置
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://book.kdjkln.asia/blog/1854638.sHtMl

原标题：golang 系统设计分库分表 id 全局生成策略
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://book.kdjkln.asia/blog/9188016.sHtMl

原标题：实战：对象存储断点续传下载实践
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://book.kdjkln.asia/blog/6993409.sHtMl

原标题：Practice：简易限流器分布式版本Redis实现
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://book.kdjkln.asia/blog/0563376.sHtMl

原标题：数据库主从延迟业务兼容处理
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://book.kdjkln.asia/blog/1658372.sHtMl

原标题：golang 系统设计分布式事务几种方案优缺点
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://book.kdjkln.asia/blog/8305137.sHtMl


二、踩坑排错｜Troubleshooting
原标题：安全复盘：消息队列未授权访问安全加固
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://book.kdjkln.asia/blog/5421775.sHtMl

原标题：安全笔记：Cookie安全属性SecureHttpOnly
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://book.kdjkln.asia/blog/4304951.sHtMl

原标题：系统时间同步定时任务偏移
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://book.kdjkln.asia/blog/9412527.sHtMl

原标题：Hands‑on：简易消息推送服务开发实践
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://book.kdjkln.asia/blog/6934269.sHtMl

原标题：golang 系统设计 sql 注入 xss 防护实践
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://book.kdjkln.asia/blog/7180654.sHtMl

原标题：golang 链路 traceId 透传中间件
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://book.kdjkln.asia/blog/6733581.sHtMl

原标题：架构笔记：缓存雪崩缓存击穿架构防护方案
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://book.kdjkln.asia/blog/3747935.sHtMl

原标题：Practice：实现请求ID透传全链路日志实践
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://book.kdjkln.asia/blog/8894650.sHtMl

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://book.kdjkln.asia/blog/6995851.sHtMl

原标题：golang docker compose 依赖启动顺序
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://book.kdjkln.asia/blog/8677777.sHtMl

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://book.kdjkln.asia/blog/1179508.sHtMl

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://book.kdjkln.asia/blog/8240849.sHtMl

原标题：方案设计：多租户系统架构三种实现模式对比
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://book.kdjkln.asia/blog/4447677.sHtMl

原标题：golang mysql 读写分离简单实现
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://book.kdjkln.asia/blog/4206914.sHtMl

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://book.kdjkln.asia/blog/4990595.sHtMl

原标题：golang 系统设计指标聚合计算存储选型对比
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://book.kdjkln.asia/blog/9688093.sHtMl

原标题：golang 系统设计回调签名校验防伪造实现
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://book.kdjkln.asia/blog/5909160.sHtMl

原标题：项目实践：定时任务防重复执行落地实践
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://book.kdjkln.asia/blog/4025488.sHtMl

原标题：golang 参数校验业务接口处理
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://book.kdjkln.asia/blog/9996946.sHtMl

原标题：实战：基于内存实现简单消息广播组件
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://book.kdjkln.asia/blog/3476092.sHtMl

原标题：golang 系统设计代码评审高效沟通原则思路
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://book.kdjkln.asia/blog/7058312.sHtMl

原标题：开发记录：跨域中间件完整配置与边界处理
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://book.kdjkln.asia/blog/6702733.sHtMl

原标题：批量数据处理脚本编写技巧
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://book.kdjkln.asia/blog/9517305.sHtMl

原标题：nodejs 集成测试业务流程编写
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://book.kdjkln.asia/blog/5492193.sHtMl

原标题：golang redis 连接池参数最佳值
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://book.kdjkln.asia/blog/2521230.sHtMl

原标题：实践：前后端时间格式统一规范落地实践
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://book.kdjkln.asia/blog/9542247.sHtMl

原标题：Hands‑on：简易频率统计组件Redis实现
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.kdjkln.asia/blog/9619310.sHtMl

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://book.kdjkln.asia/blog/4580936.sHtMl

原标题：缓存过期打散防止缓存雪崩
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://book.kdjkln.asia/blog/0811062.sHtMl

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://book.kdjkln.asia/blog/7358438.sHtMl

原标题：主干开发团队代码合并策略
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://book.kdjkln.asia/blog/2682858.sHtMl

原标题：vite 插件开发自定义构建逻辑
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://book.kdjkln.asia/blog/8556443.sHtMl

原标题：服务器时钟同步任务错乱修复
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://book.kdjkln.asia/blog/8453431.sHtMl

原标题：golang 系统设计第三方接口调用封装思路
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://book.kdjkln.asia/blog/5718830.sHtMl

原标题：golang docker 镜像构建最佳实践
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://book.kdjkln.asia/blog/5038412.sHtMl

原标题：golang docker 部署 kafka 本地调试
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://book.kdjkln.asia/blog/0037293.sHtMl

原标题：CORS 跨域问题多种解决方案
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://book.kdjkln.asia/blog/3609680.sHtMl

原标题：文件监控服务自动重启开发
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://book.kdjkln.asia/blog/0108938.sHtMl

原标题：Debug：分布式会话时钟不同步令牌提前失效
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://book.kdjkln.asia/blog/6081843.sHtMl

原标题：SDK 版本兼容线上崩溃修复
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://book.kdjkln.asia/blog/0161434.sHtMl

三、实战开发｜Practice
原标题：golang 系统设计传输加密 tls 配置要点
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://book.kdjkln.asia/blog/2142619.sHtMl

原标题：实战：Nginx实现文件限速下载配置实践
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://book.kdjkln.asia/blog/6943500.sHtMl

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://book.kdjkln.asia/blog/4168240.sHtMl

原标题：golang 系统设计消息重试次数间隔策略设置
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://book.kdjkln.asia/blog/8297053.sHtMl

原标题：golang 系统设计 pre‑commit 钩子本地代码校验
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://book.kdjkln.asia/blog/3007750.sHtMl

原标题：golang mongodb 分页性能优化技巧
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://book.kdjkln.asia/blog/4874168.sHtMl

原标题：多操作系统开发兼容处理
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://book.kdjkln.asia/blog/6936464.sHtMl

原标题：全局异常处理器接口返回统一
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://book.kdjkln.asia/blog/2175728.sHtMl

原标题：坑点：版本号语义化理解错误依赖版本错乱
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://book.kdjkln.asia/blog/8521111.sHtMl

原标题：golang url 参数编码处理方案
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://book.kdjkln.asia/blog/2263256.sHtMl

原标题：HelloShell：入门常用shell脚本编写
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://book.kdjkln.asia/blog/7959557.sHtMl

原标题：golang goroutine 池任务调度
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://book.kdjkln.asia/blog/9535344.sHtMl

原标题：运维笔记：系统内核参数调优生产服务器
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://book.kdjkln.asia/blog/0167287.sHtMl

原标题：Practice：模拟第三方接口超时服务降级验证
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.kdjkln.asia/blog/4620696.sHtMl

原标题：golang 系统设计 gob msgpack 序列化对比
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://book.kdjkln.asia/blog/0921965.sHtMl

原标题：golang 单元测试 table‑driven
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://book.kdjkln.asia/blog/8717789.sHtMl

原标题：golang 系统设计内存瓶颈定位优化思路
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://book.kdjkln.asia/blog/1890258.sHtMl

原标题：golang 系统设计消息 key 选择保证顺序性方案
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://book.kdjkln.asia/blog/1221108.sHtMl

原标题：线上故障：慢查询拖垮整个数据库服务
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.kdjkln.asia/blog/2486417.sHtMl

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://book.kdjkln.asia/blog/5638967.sHtMl

原标题：数据库分表存储大表优化方案
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://book.kdjkln.asia/blog/0005724.sHtMl

原标题：WebSocket 聊天室实时通讯开发
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://book.kdjkln.asia/blog/2731424.sHtMl

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://book.kdjkln.asia/blog/4628246.sHtMl

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://book.kdjkln.asia/blog/8161117.sHtMl

原标题：新手指南：看懂开源项目的Issue与PR
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://book.kdjkln.asia/blog/2352509.sHtMl

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://book.kdjkln.asia/blog/7185030.sHtMl

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://book.kdjkln.asia/blog/1272733.sHtMl

原标题：快速入门gRPC基础概念与简单示例
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://book.kdjkln.asia/blog/5405671.sHtMl

原标题：golang 系统设计 csrf 接口防护实现
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://book.kdjkln.asia/blog/2729954.sHtMl

原标题：JWT 令牌过期异常处理
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://book.kdjkln.asia/blog/2332640.sHtMl

原标题：性能复盘：接口响应从800ms优化到50ms全过程
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://book.kdjkln.asia/blog/4347903.sHtMl

原标题：开源实践：开源项目本地调试构建排坑经验
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://book.kdjkln.asia/blog/0968015.sHtMl

原标题：架构复盘：限流系统架构防止恶意流量冲击
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://book.kdjkln.asia/blog/9599614.sHtMl

原标题：项目实践：幂等表实现接口幂等业务实践
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://book.kdjkln.asia/blog/2968671.sHtMl

原标题：golang mysql 读写分离简单实现
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://book.kdjkln.asia/blog/7107953.sHtMl

原标题：golang 系统设计开源项目维护简单经验分享
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://book.kdjkln.asia/blog/9309278.sHtMl

原标题：Hands‑on：简易事件驱动架构原型开发
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://book.kdjkln.asia/blog/7343243.sHtMl

原标题：golang channel 通道并发处理
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://book.kdjkln.asia/blog/4105980.sHtMl

原标题：express 请求参数校验处理
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://book.kdjkln.asia/blog/2553202.sHtMl

原标题：nodejs 集群模式多核利用实现
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://book.kdjkln.asia/blog/8511176.sHtMl

四、架构设计｜Architecture
原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://book.kdjkln.asia/blog/5890348.sHtMl

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://book.kdjkln.asia/blog/2208813.sHtMl

原标题：golang redis 过期 key 监听业务
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://book.kdjkln.asia/blog/1094467.sHtMl

原标题：golang redis 五种数据结构实战
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://book.kdjkln.asia/blog/0306991.sHtMl

原标题：golang github actions 完整工作流示例
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://book.kdjkln.asia/blog/7615044.sHtMl

原标题：git stash 代码暂存切换分支
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://book.kdjkln.asia/blog/8952035.sHtMl

原标题：部署实践：服务器防火墙安全组配置实践
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://book.kdjkln.asia/blog/0386643.sHtMl

原标题：Git 子模块更新代码不全修复
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://book.kdjkln.asia/blog/2241365.sHtMl

原标题：本地简易配置中心动态管理
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://book.kdjkln.asia/blog/9133939.sHtMl

原标题：方案设计：统一ID生成服务架构对比雪花算法
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://book.kdjkln.asia/blog/3557860.sHtMl

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://book.kdjkln.asia/blog/1935511.sHtMl

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://book.kdjkln.asia/blog/0255735.sHtMl

原标题：golang alertmanager 钉钉告警推送
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://book.kdjkln.asia/blog/8145991.sHtMl

原标题：部署复盘：蓝绿发布实现零停机业务更新
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://book.kdjkln.asia/blog/7958034.sHtMl

原标题：golang 系统设计埋点数据上报方案
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://book.kdjkln.asia/blog/0413997.sHtMl

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://book.kdjkln.asia/blog/8964540.sHtMl

原标题：golang redis 地理位置 geo 使用
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.kdjkln.asia/blog/3814001.sHtMl

原标题：HelloWorld：快速上手新项目最小可运行示例
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://book.kdjkln.asia/blog/9401807.sHtMl

?
