最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计分布式锁选型对比
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.u7m9gx.asia/arts/129124.Doc

原标题：Git 代码冲突正确处理方式
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://wiki.u7m9gx.asia/arts/313239.Doc

原标题：方案设计：分布式分页查询架构难点处理
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://wiki.u7m9gx.asia/arts/146983.Doc

原标题：Practice：实现业务操作日志记录中间件实践
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.u7m9gx.asia/arts/904032.Doc

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://wiki.u7m9gx.asia/arts/987772.Doc

原标题：Architecture：事件溯源架构模式适用业务场景
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.u7m9gx.asia/arts/326844.Doc

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.u7m9gx.asia/arts/552862.Doc

原标题：golang 系统设计第三方调用超时重试熔断
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://wiki.u7m9gx.asia/arts/317217.Doc

原标题：实践：消息队列死信处理业务落地实践
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.u7m9gx.asia/arts/972825.Doc

原标题：轻量 API 后端接口服务快速开发
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.u7m9gx.asia/arts/252636.Doc

原标题：前后端会话登录状态持久化
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.u7m9gx.asia/arts/196327.Doc

原标题：分布式 ID 生成器高并发实现
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.u7m9gx.asia/arts/564988.Doc

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.u7m9gx.asia/arts/190848.Doc

原标题：Architecture：大文件上传下载系统架构设计
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.u7m9gx.asia/arts/822841.Doc

原标题：版本升级服务启动失败处理
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.u7m9gx.asia/arts/690359.Doc

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.u7m9gx.asia/arts/780869.Doc

原标题：快速上手阅读开源项目源码的入门思路
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://wiki.u7m9gx.asia/arts/759323.Doc

原标题：golang 系统设计技术方案评审关注点清单参考
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://wiki.u7m9gx.asia/arts/834217.Doc

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.u7m9gx.asia/arts/199306.Doc

原标题：实战：Nginx负载均衡多种策略配置实践
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://wiki.u7m9gx.asia/arts/051647.Doc

原标题：golang docker 基础命令实操汇总
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.u7m9gx.asia/arts/642744.Doc

原标题：golang 系统设计 canary 金丝雀部署实操
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://wiki.u7m9gx.asia/arts/053316.Doc

原标题：性能复盘：接口响应从800ms优化到50ms全过程
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.u7m9gx.asia/arts/778804.Doc

原标题：调优方案：Web服务内核socket参数调优
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.u7m9gx.asia/arts/100428.Doc

原标题：缓存穿透防护保护数据库
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.u7m9gx.asia/arts/592989.Doc

原标题：Hands‑on：简易短链接服务完整开发实践
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.u7m9gx.asia/arts/822917.Doc

原标题：Git commit 钩子提交规范校验
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://wiki.u7m9gx.asia/arts/427054.Doc

原标题：golang 系统设计分表跨表 join 业务处理方案
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.u7m9gx.asia/arts/784163.Doc

原标题：Architecture：日志、监控、告警整套可观测架构
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://wiki.u7m9gx.asia/arts/673952.Doc

原标题：新手向：看懂项目README的正确阅读姿势
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://wiki.u7m9gx.asia/arts/459841.Doc

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://wiki.u7m9gx.asia/arts/686034.Doc

原标题：数据库主从延迟业务兼容处理
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.u7m9gx.asia/arts/057222.Doc

原标题：Performance：数据库大表优化，冷热数据分离
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.u7m9gx.asia/arts/641404.Doc

原标题：golang 系统设计防重复提交实现
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.u7m9gx.asia/arts/457999.Doc

原标题：从零学习简单分页逻辑实现思路
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://wiki.u7m9gx.asia/arts/792108.Doc

原标题：Practice：实现请求重试组件支持退避策略
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://wiki.u7m9gx.asia/arts/372852.Doc

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://wiki.u7m9gx.asia/arts/268872.Doc

原标题：golang 系统设计 http 接口基准测试实操示例
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.u7m9gx.asia/arts/253669.Doc

原标题：异步编程 Promise 执行流程解析
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.u7m9gx.asia/arts/930695.Doc

原标题：Shell 脚本自动化命令编写
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.u7m9gx.asia/arts/090852.Doc


二、踩坑排错｜Troubleshooting
原标题：golang redis 分布式计数器开发
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://wiki.u7m9gx.asia/arts/020585.Doc

原标题：Architecture：CI/CD流水线架构完整设计思考
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://wiki.u7m9gx.asia/arts/051481.Doc

原标题：TLS 版本兼容 HTTPS 握手失败
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://wiki.u7m9gx.asia/arts/529202.Doc

原标题：Docker 多阶段构建镜像瘦身
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.u7m9gx.asia/arts/001469.Doc

原标题：golang 简单爬虫请求防封禁
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://wiki.u7m9gx.asia/arts/824830.Doc

原标题：Performance：避免大报文，减少内存占用优化
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.u7m9gx.asia/arts/398217.Doc

原标题：项目实践：消息队列消息确认机制业务实践
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://wiki.u7m9gx.asia/arts/890383.Doc

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.u7m9gx.asia/arts/545544.Doc

原标题：nodejs jwt 登录鉴权完整示例
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.u7m9gx.asia/arts/695216.Doc

原标题：golang redis 持久化 RDB AOF 对比
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://wiki.u7m9gx.asia/arts/890848.Doc

原标题：golang 系统设计状态字段枚举约束设计思路
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://wiki.u7m9gx.asia/arts/016492.Doc

原标题：golang 系统设计日志与 traceId 关联打印实现
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://wiki.u7m9gx.asia/arts/799054.Doc

原标题：golang docker 容器资源限制设置
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://wiki.u7m9gx.asia/arts/316626.Doc

原标题：OpenSource：开源项目README高质量编写指南
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://wiki.u7m9gx.asia/arts/458871.Doc

原标题：图片上传预览格式大小处理
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.u7m9gx.asia/arts/667831.Doc

原标题：golang 系统设计多级缓存更新策略
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://wiki.u7m9gx.asia/arts/893547.Doc

原标题：Practice：实现请求大小限制中间件防护大报文
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.u7m9gx.asia/arts/424808.Doc

原标题：golang mysql 读写分离简单实现
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.u7m9gx.asia/arts/234628.Doc

原标题：golang 协程泄露问题排查方法
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://wiki.u7m9gx.asia/arts/556363.Doc

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.u7m9gx.asia/arts/994100.Doc

原标题：golang toml 配置文件解析教程
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://wiki.u7m9gx.asia/arts/137625.Doc

原标题：golang 系统设计死信队列 dlq 业务落地完整流程
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://wiki.u7m9gx.asia/arts/897572.Doc

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.u7m9gx.asia/arts/466028.Doc

原标题：Hands‑on：编写GitLabCI配置自动测试部署
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://wiki.u7m9gx.asia/arts/889572.Doc

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.u7m9gx.asia/arts/497399.Doc

原标题：效率笔记：GitWorkflow团队协作规范模板
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://wiki.u7m9gx.asia/arts/612943.Doc

原标题：设计思考：缓存分层架构设计与失效处理策略
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.u7m9gx.asia/arts/337430.Doc

原标题：golang 系统设计 api 接口兼容性设计原则
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.u7m9gx.asia/arts/994329.Doc

原标题：数据库事务 ACID 原理讲解
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://wiki.u7m9gx.asia/arts/896322.Doc

原标题：golang 系统设计容器健康检查设计思路
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://wiki.u7m9gx.asia/arts/393962.Doc

原标题：轻量 API 后端接口服务快速开发
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.u7m9gx.asia/arts/647379.Doc

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://wiki.u7m9gx.asia/arts/080148.Doc

原标题：Hands‑on：简易连接池原型实现理解原理
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.u7m9gx.asia/arts/723852.Doc

原标题：架构复盘：数据库索引架构设计原则与边界
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.u7m9gx.asia/arts/594730.Doc

原标题：Practice：实现请求重试组件支持退避策略
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.u7m9gx.asia/arts/375558.Doc

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.u7m9gx.asia/arts/804087.Doc

原标题：golang 告警推送钉钉机器人实现
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://wiki.u7m9gx.asia/arts/800960.Doc

原标题：nodejs 定时任务生产环境避坑
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.u7m9gx.asia/arts/779404.Doc

原标题：nodejs 信号处理优雅关闭服务
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.u7m9gx.asia/arts/823215.Doc

原标题：golang 系统设计传输加密 tls 配置要点
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://wiki.u7m9gx.asia/arts/263595.Doc

三、实战开发｜Practice
原标题：批量异步处理系统业务落地
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.u7m9gx.asia/arts/694871.Doc

原标题：golang 系统设计技术方案文档模板参考
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.u7m9gx.asia/arts/274455.Doc

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.u7m9gx.asia/arts/555167.Doc

原标题：Performance：长连接管理优化减少连接重建开销
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://wiki.u7m9gx.asia/arts/161133.Doc

原标题：实战：多版本SDK兼容业务改造实践
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.u7m9gx.asia/arts/863400.Doc

原标题：golang 系统设计 k8s 集群安全配置梳理
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://wiki.u7m9gx.asia/arts/578245.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://wiki.u7m9gx.asia/arts/119242.Doc

原标题：系统时间同步定时任务偏移
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.u7m9gx.asia/arts/937401.Doc

原标题：接口签名验签完整安全方案
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.u7m9gx.asia/arts/381938.Doc

原标题：golang redis 连接池参数最佳值
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://wiki.u7m9gx.asia/arts/720800.Doc

原标题：架构复盘：慢查询治理架构层面优化手段
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.u7m9gx.asia/arts/240721.Doc

原标题：开发复盘：数据库批量更新优化性能实践
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.u7m9gx.asia/arts/403629.Doc

原标题：容器软链接文件权限修复
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://wiki.u7m9gx.asia/arts/064438.Doc

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.u7m9gx.asia/arts/204196.Doc

原标题：避坑：定时任务重复执行带来业务脏数据
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://wiki.u7m9gx.asia/arts/619653.Doc

原标题：golang 系统设计监控告警体系搭建思路
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://wiki.u7m9gx.asia/arts/148391.Doc

原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://wiki.u7m9gx.asia/arts/030007.Doc

原标题：安全实践：SQL注入产生场景与完整防御手段
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://wiki.u7m9gx.asia/arts/619683.Doc

原标题：Issue：开源项目升级大版本后API不兼容踩坑
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://wiki.u7m9gx.asia/arts/026807.Doc

原标题：实战项目：WSL开发环境完整配置实操
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://wiki.u7m9gx.asia/arts/223192.Doc

原标题：RPC 报文大小上限调优大请求
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://wiki.u7m9gx.asia/arts/823922.Doc

原标题：分页逻辑错误数据漏查修复
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://wiki.u7m9gx.asia/arts/931990.Doc

原标题：Practice：实现业务操作日志记录中间件实践
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://wiki.u7m9gx.asia/arts/208062.Doc

原标题：HelloShell：入门常用shell脚本编写
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.u7m9gx.asia/arts/537081.Doc

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.u7m9gx.asia/arts/938549.Doc

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.u7m9gx.asia/arts/318628.Doc

原标题：缓存基础原理与简单代码实现
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://wiki.u7m9gx.asia/arts/159653.Doc

原标题：实践：接口参数自动校验业务落地实践
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.u7m9gx.asia/arts/323936.Doc

原标题：golang 优雅停机服务关闭实现
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://wiki.u7m9gx.asia/arts/160570.Doc

原标题：记一次升级操作系统内核引发服务不稳定
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://wiki.u7m9gx.asia/arts/124107.Doc

原标题：golang 配置热更新不重启服务
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://wiki.u7m9gx.asia/arts/022860.Doc

原标题：golang 系统设计链路追踪架构简单讲解
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.u7m9gx.asia/arts/311648.Doc

原标题：golang 系统设计 mq 消息顺序性保证思路
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.u7m9gx.asia/arts/450067.Doc

原标题：架构笔记：数据库连接池架构参数调优思路
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://wiki.u7m9gx.asia/arts/620988.Doc

原标题：Performance：避免大报文，减少内存占用优化
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://wiki.u7m9gx.asia/arts/122056.Doc

原标题：golang 系统设计索引设计通用方法论汇总
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://wiki.u7m9gx.asia/arts/534714.Doc

原标题：设计思考：缓存分层架构设计与失效处理策略
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.u7m9gx.asia/arts/230018.Doc

原标题：golang net/http 超时全套配置
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.u7m9gx.asia/arts/527693.Doc

原标题：Shell 脚本自动化命令编写
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.u7m9gx.asia/arts/145187.Doc

原标题：AI实践：大模型生成测试用例实践与校验
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.u7m9gx.asia/arts/649634.Doc

四、架构设计｜Architecture
原标题：golang redis set 集合去重业务
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://wiki.u7m9gx.asia/arts/647303.Doc

原标题：部署实践：服务器SSH安全加固配置实践
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.u7m9gx.asia/arts/208458.Doc

原标题：操作系统内核版本适配服务
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://wiki.u7m9gx.asia/arts/451152.Doc

原标题：缓存基础原理与简单代码实现
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.u7m9gx.asia/arts/904017.Doc

原标题：vue3 组合式 API 业务开发实战
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://wiki.u7m9gx.asia/arts/758814.Doc

原标题：前端图片懒加载性能优化
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://wiki.u7m9gx.asia/arts/567495.Doc

原标题：golang 系统设计 e2e 端到端测试简单落地思路
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://wiki.u7m9gx.asia/arts/752216.Doc

原标题：golang 系统设计 api 网关核心能力梳理
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://wiki.u7m9gx.asia/arts/756677.Doc

原标题：安全笔记：GitHubAction密钥安全管理
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.u7m9gx.asia/arts/258166.Doc

原标题：极简方式搭建个人技术文档站点
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.u7m9gx.asia/arts/270471.Doc

原标题：vite 项目配置与构建提速技巧
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.u7m9gx.asia/arts/795137.Doc

原标题：golang alertmanager 钉钉告警推送
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.u7m9gx.asia/arts/298982.Doc

原标题：新手教程：Git撤销错误提交的几种常用方式
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://wiki.u7m9gx.asia/arts/480816.Doc

原标题：快速入门日志打印与日志分级基础用法
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.u7m9gx.asia/arts/286683.Doc

原标题：运维笔记：线上服务健康检查脚本编写
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.u7m9gx.asia/arts/829502.Doc

原标题：入门实践：简单错误码设计与使用规范
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.u7m9gx.asia/arts/782252.Doc

原标题：golang k8s helm chart 简单编写
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://wiki.u7m9gx.asia/arts/159366.Doc

原标题：golang k8s 日志收集 efk 简单架构
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.u7m9gx.asia/arts/537601.Doc

?
