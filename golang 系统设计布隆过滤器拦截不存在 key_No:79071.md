最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计布隆过滤器拦截不存在 key
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.ea7a5m.asia/arts/047682.Doc

原标题：golang redis lua 脚本原子操作
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.ea7a5m.asia/arts/907643.Doc

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.ea7a5m.asia/arts/480795.Doc

原标题：Practice：实现限流之后友好业务返回处理
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.ea7a5m.asia/arts/272962.Doc

原标题：golang 布隆过滤器实现去重
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://wiki.ea7a5m.asia/arts/901050.Doc

原标题：golang docker 部署 kafka 本地调试
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://wiki.ea7a5m.asia/arts/844936.Doc

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.ea7a5m.asia/arts/578364.Doc

原标题：Security：Docker镜像安全扫描漏洞修复
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.ea7a5m.asia/arts/224536.Doc

原标题：golang 令牌桶限流中间件 gin
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://wiki.ea7a5m.asia/arts/042179.Doc

原标题：一次数据库死锁现场分析与解决方案记录
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.ea7a5m.asia/arts/209906.Doc

原标题：Performance：避免循环查询N+1问题完整优化
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.ea7a5m.asia/arts/953494.Doc

原标题：Hands‑on：简易消息推送服务开发实践
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://wiki.ea7a5m.asia/arts/054714.Doc

原标题：坑点：环境配置写死代码，上线忘记修改
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.ea7a5m.asia/arts/477691.Doc

原标题：前端图片懒加载性能优化
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.ea7a5m.asia/arts/040200.Doc

原标题：实战项目：容器资源限制配置压力测试实践
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://wiki.ea7a5m.asia/arts/440640.Doc

原标题：缓存穿透击穿雪崩全套防护
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://wiki.ea7a5m.asia/arts/797969.Doc

原标题：快速入门：API接口调试完整实操步骤
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.ea7a5m.asia/arts/303912.Doc

原标题：手写简易 MQ 理解消息存储消费
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://wiki.ea7a5m.asia/arts/930678.Doc

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.ea7a5m.asia/arts/516758.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.ea7a5m.asia/arts/631499.Doc

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://wiki.ea7a5m.asia/arts/145686.Doc

原标题：快速入门OpenAPI文档生成基础实践
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://wiki.ea7a5m.asia/arts/402425.Doc

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.ea7a5m.asia/arts/626580.Doc

原标题：部署实践：HTTPS证书自动续期配置实践
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.ea7a5m.asia/arts/480812.Doc

原标题：前端组件库按需加载性能优化
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://wiki.ea7a5m.asia/arts/406378.Doc

原标题：golang 内存缓存简单实现方案
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://wiki.ea7a5m.asia/arts/397124.Doc

原标题：Hands‑on：简易消息推送服务开发实践
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://wiki.ea7a5m.asia/arts/171851.Doc

原标题：从零搭建简单CLI命令行工具
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://wiki.ea7a5m.asia/arts/057477.Doc

原标题：多操作系统开发兼容处理
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.ea7a5m.asia/arts/683329.Doc

原标题：nodejs 日志轮转生产环境配置
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.ea7a5m.asia/arts/661532.Doc

原标题：批量操作分批处理防止 OOM
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://wiki.ea7a5m.asia/arts/117362.Doc

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://wiki.ea7a5m.asia/arts/895174.Doc

原标题：golang ci 流水线漏洞扫描依赖检查
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.ea7a5m.asia/arts/743719.Doc

原标题：golang 系统设计限流熔断降级组合使用
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.ea7a5m.asia/arts/735793.Doc

原标题：Security：Docker镜像安全扫描漏洞修复
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://wiki.ea7a5m.asia/arts/552708.Doc

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.ea7a5m.asia/arts/537040.Doc

原标题：端口占用释放资源重启服务
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://wiki.ea7a5m.asia/arts/479424.Doc

原标题：线程池拒绝策略任务丢失防护
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.ea7a5m.asia/arts/868244.Doc

原标题：golang channel 通道并发处理
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://wiki.ea7a5m.asia/arts/921456.Doc

原标题：数据库读写分离性能优化
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://wiki.ea7a5m.asia/arts/649087.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计秒杀防超卖方案
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://wiki.ea7a5m.asia/arts/171651.Doc

原标题：golang 系统设计监控缺失指标补全完整流程
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://wiki.ea7a5m.asia/arts/321328.Doc

原标题：DevOps：环境配置管理区分开发测试生产
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://wiki.ea7a5m.asia/arts/431558.Doc

原标题：实战项目：多实例部署会话一致性验证实践
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.ea7a5m.asia/arts/129618.Doc

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://wiki.ea7a5m.asia/arts/641192.Doc

原标题：golang k8s 本地 minikube 调试应用
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://wiki.ea7a5m.asia/arts/019818.Doc

原标题：vite 插件开发自定义构建逻辑
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://wiki.ea7a5m.asia/arts/968781.Doc

原标题：golang etcd 配置中心简单使用
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.ea7a5m.asia/arts/656918.Doc

原标题：项目实践：数据库慢日志采集分析落地实践
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.ea7a5m.asia/arts/056985.Doc

原标题：大事务拆分防止连接池耗尽
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://wiki.ea7a5m.asia/arts/030145.Doc

原标题：golang 布隆过滤器实现去重
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://wiki.ea7a5m.asia/arts/892969.Doc

原标题：golang mongodb 聚合管道实操案例
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.ea7a5m.asia/arts/188544.Doc

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://wiki.ea7a5m.asia/arts/237080.Doc

原标题：请求工具封装统一异常处理
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.ea7a5m.asia/arts/758195.Doc

原标题：实战：Nginx实现文件限速下载配置实践
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.ea7a5m.asia/arts/155770.Doc

原标题：golang 系统设计 protobuf 命名规范最佳实践
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://wiki.ea7a5m.asia/arts/591699.Doc

原标题：golang 系统设计文件存储选型对比
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.ea7a5m.asia/arts/137122.Doc

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.ea7a5m.asia/arts/795732.Doc

原标题：定时任务周期调度 demo 开发
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://wiki.ea7a5m.asia/arts/609856.Doc

原标题：新手指南：本地多版本环境共存配置
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.ea7a5m.asia/arts/125477.Doc

原标题：golang redis 过期策略内存淘汰
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://wiki.ea7a5m.asia/arts/748304.Doc

原标题：golang 系统设计网关错误重试超时处理策略
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.ea7a5m.asia/arts/160807.Doc

原标题：批量数据处理脚本编写技巧
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://wiki.ea7a5m.asia/arts/156419.Doc

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.ea7a5m.asia/arts/554666.Doc

原标题：golang redis 计数器防超卖示例
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://wiki.ea7a5m.asia/arts/203170.Doc

原标题：golang docker compose 依赖启动顺序
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.ea7a5m.asia/arts/386817.Doc

原标题：架构笔记：OAuth2授权服务架构模式拆解
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.ea7a5m.asia/arts/995071.Doc

原标题：Security：RPC调用身份认证安全加固
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.ea7a5m.asia/arts/647603.Doc

原标题：安全实践：输入输出双向过滤安全最佳实践
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.ea7a5m.asia/arts/671760.Doc

原标题：golang websocket 消息广播实现
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.ea7a5m.asia/arts/917584.Doc

原标题：golang 系统设计开源项目安全漏洞处理流程
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.ea7a5m.asia/arts/092435.Doc

原标题：golang 系统设计分库分表本地测试调试技巧
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://wiki.ea7a5m.asia/arts/459817.Doc

原标题：新手指南：虚拟机WSL开发环境入门配置
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.ea7a5m.asia/arts/640580.Doc

原标题：golang 系统设计本地缓存更新失效方案实现
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://wiki.ea7a5m.asia/arts/234780.Doc

原标题：Hands‑on：本地模拟分布式锁失效场景测试
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://wiki.ea7a5m.asia/arts/609081.Doc

原标题：实战项目：GitSubmodule管理多仓库实践
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://wiki.ea7a5m.asia/arts/818665.Doc

原标题：设计思考：系统限流熔断降级完整防护体系
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://wiki.ea7a5m.asia/arts/378220.Doc

原标题：golang 系统设计分表字段选择路由规则设计
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.ea7a5m.asia/arts/894364.Doc

原标题：Performance：缓存策略优化，降低数据库压力
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://wiki.ea7a5m.asia/arts/892374.Doc

原标题：架构笔记：分布式系统常见一致性模型梳理
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://wiki.ea7a5m.asia/arts/200699.Doc

三、实战开发｜Practice
原标题：golang 系统设计多租户数据隔离方案
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.ea7a5m.asia/arts/474622.Doc

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.ea7a5m.asia/arts/612441.Doc

原标题：Architecture：配置中心架构，动态配置设计思路
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://wiki.ea7a5m.asia/arts/552584.Doc

原标题：golang 消息死信处理业务逻辑
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.ea7a5m.asia/arts/557266.Doc

原标题：golang minio 对象存储接口开发
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://wiki.ea7a5m.asia/arts/317926.Doc

原标题：golang redis bitmap 位图统计实现
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.ea7a5m.asia/arts/341362.Doc

原标题：golang 集成测试启动测试数据库
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.ea7a5m.asia/arts/960187.Doc

原标题：坑点：gitsubmodule子模块更新失败踩坑
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://wiki.ea7a5m.asia/arts/937585.Doc

原标题：golang 系统设计索引设计通用方法论汇总
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.ea7a5m.asia/arts/318666.Doc

原标题：golang ci 流水线代码质量扫描集成
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://wiki.ea7a5m.asia/arts/947996.Doc

原标题：Architecture：中小型后端服务整体架构设计复盘
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://wiki.ea7a5m.asia/arts/662314.Doc

原标题：ICMP 放通网络丢包问题修复
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.ea7a5m.asia/arts/934684.Doc

原标题：踩坑：大事务引发数据库连接池耗尽
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://wiki.ea7a5m.asia/arts/218890.Doc

原标题：实践：前后端时间格式统一规范落地实践
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://wiki.ea7a5m.asia/arts/718361.Doc

原标题：记一次升级操作系统内核引发服务不稳定
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.ea7a5m.asia/arts/482470.Doc

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://wiki.ea7a5m.asia/arts/133333.Doc

原标题：TCP 心跳检测清理僵死连接
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://wiki.ea7a5m.asia/arts/004296.Doc

原标题：浏览器内存泄漏排查前端页面
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://wiki.ea7a5m.asia/arts/326448.Doc

原标题：golang 系统设计 ci 流水线安全管控思路
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.ea7a5m.asia/arts/980816.Doc

原标题：缓存穿透防护保护数据库
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.ea7a5m.asia/arts/334154.Doc

原标题：JWT 令牌过期异常处理
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://wiki.ea7a5m.asia/arts/445874.Doc

原标题：golang 系统设计密码存储哈希加盐实现
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://wiki.ea7a5m.asia/arts/446169.Doc

原标题：端口占用访问失败排查方案
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://wiki.ea7a5m.asia/arts/619364.Doc

原标题：OAuth2 第三方登录服务搭建
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://wiki.ea7a5m.asia/arts/316633.Doc

原标题：效率笔记：Makefile项目构建脚本编写实践
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.ea7a5m.asia/arts/787857.Doc

原标题：安全复盘：日志打印敏感信息泄露治理
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.ea7a5m.asia/arts/319296.Doc

原标题：golang 简单爬虫请求防封禁
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://wiki.ea7a5m.asia/arts/778091.Doc

原标题：golang 系统设计日志规范结构化日志落地
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://wiki.ea7a5m.asia/arts/658026.Doc

原标题：架构复盘：消息死信处理架构避免消息丢失
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.ea7a5m.asia/arts/901546.Doc

原标题：golang 系统设计错误码体系完整设计
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.ea7a5m.asia/arts/974766.Doc

原标题：Performance：数据库大表优化，冷热数据分离
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://wiki.ea7a5m.asia/arts/823884.Doc

原标题：golang redis 客户端业务使用
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.ea7a5m.asia/arts/639869.Doc

原标题：Security：文件上传漏洞攻击面完整防护方案
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://wiki.ea7a5m.asia/arts/722481.Doc

原标题：复盘总结：技术方案文档模板架构设计文档
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://wiki.ea7a5m.asia/arts/590015.Doc

原标题：Hands‑on：编写GitLabCI配置自动测试部署
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.ea7a5m.asia/arts/823325.Doc

原标题：golang docker 基础命令实操汇总
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.ea7a5m.asia/arts/054934.Doc

原标题：运维笔记：CI流水线缓存策略加速构建速度
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.ea7a5m.asia/arts/951200.Doc

原标题：避坑：Nginx配置错误导致请求丢失Header
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://wiki.ea7a5m.asia/arts/015540.Doc

原标题：golang 系统设计一致性哈希原理讲解
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.ea7a5m.asia/arts/326868.Doc

原标题：Architecture：API网关核心能力与组件拆分
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.ea7a5m.asia/arts/219194.Doc

四、架构设计｜Architecture
原标题：防火墙 IP 白名单回调接口放行
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://wiki.ea7a5m.asia/arts/306451.Doc

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://wiki.ea7a5m.asia/arts/924002.Doc

原标题：golang lru 缓存淘汰算法编写
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://wiki.ea7a5m.asia/arts/160395.Doc

原标题：静态站点自动部署发布方案
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.ea7a5m.asia/arts/573655.Doc

原标题：Nginx 反向代理路由配置实战
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://wiki.ea7a5m.asia/arts/986616.Doc

原标题：golang toml 配置文件解析教程
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://wiki.ea7a5m.asia/arts/623844.Doc

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：http://wiki.ea7a5m.asia/arts/415848.Doc

原标题：golang kafka 批量发送消费优化
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://wiki.ea7a5m.asia/arts/872499.Doc

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.ea7a5m.asia/arts/235760.Doc

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.ea7a5m.asia/arts/323387.Doc

原标题：开发复盘：数据库批量更新优化性能实践
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://wiki.ea7a5m.asia/arts/292720.Doc

原标题：新手向：配置项目eslint/prettier代码格式化
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://wiki.ea7a5m.asia/arts/679812.Doc

原标题：静态网页 HTML CSS 快速入门实战
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.ea7a5m.asia/arts/499537.Doc

原标题：Architecture：API网关核心能力与组件拆分
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://wiki.ea7a5m.asia/arts/125740.Doc

原标题：golang 配置文件多环境加载
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://wiki.ea7a5m.asia/arts/812581.Doc

原标题：golang 系统设计缓存降级开关快速切库实现
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://wiki.ea7a5m.asia/arts/748824.Doc

原标题：数据库分表存储大表优化方案
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.ea7a5m.asia/arts/672219.Doc

原标题：golang 系统设计数据库基准压测简单思路
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.ea7a5m.asia/arts/743138.Doc

?
