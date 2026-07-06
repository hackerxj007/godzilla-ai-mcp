# godzilla-ai-mcp
哥斯拉4.0.1,415版本都支持的mcp插件


插件加载即可食用，可部署到内部局域网网页一起多人运动
<img width="1162" height="530" alt="image" src="https://github.com/user-attachments/assets/f21087e4-2485-4b89-973a-b269a94c2e13" />



功能截图:

<img width="2870" height="1816" alt="cf83ba7a-910c-4193-aac3-fbf8dd5aba9b" src="https://github.com/user-attachments/assets/4fa63e9c-cb32-472d-afcd-0f483bca5507" />

<img width="1104" height="1594" alt="image" src="https://github.com/user-attachments/assets/a65eaea4-e9f3-4475-bbc8-ca57a3cdf740" />

<img width="690" height="818" alt="566f6a9847e67d00af5f3daa79ac89a1" src="https://github.com/user-attachments/assets/c7c5a074-90c6-4588-878e-9df832d56a47" />
<img width="776" height="776" alt="ed76d2c4d6cd82decc65668abd334304" src="https://github.com/user-attachments/assets/b01a39ae-f16a-47ce-afb7-c25de558200b" />


目前可用的功能按类别整理如下：

🔌 连接管理

新建连接 — 通过 URL/密码/密钥/加密方式连接 webshell

已保存连接 — 列出所有保存的 shell 记录

活跃会话 — 查看当前已连接的会话

断开连接 — 断开指定或当前会话

测试连通性 — 检测当前 shell 是否存活


📁 文件操作

列出文件 — 浏览目标系统目录（支持递归）

读取文件 — 读取文本/二进制文件内容

写入文件 — 创建或追加写入文件（自动创建目录）

上传文件 — 从本地上传文件到目标

下载文件 — 从目标下载文件到本地

删除文件 — 删除文件或目录（支持递归）


💻 命令 & 代码执行

系统命令 — 执行系统命令（cmd/bash）

代码执行 — 在 webshell 原生语言中执行代码（Java/PHP/C#/ASP）


📊 系统侦查

系统信息 — OS、主机名、IP、用户、环境变量

当前用户 — 获取 webshell 进程的用户身份

进程列表 — 列出运行中的进程

磁盘列表 — 列出磁盘分区

网络信息 — IP 地址、路由表、活动连接

屏幕截图 — 捕获目标桌面截图


🗄️ 数据库渗透

数据库探测 — 通过隧道发现内网数据库

SQL 执行 — 直连内网 MySQL/MSSQL/Oracle/PostgreSQL/SQLite 执行查询


🧠 内存马注入

注入内存马 — Servlet / Filter / Listener / Valve（Tomcat）

列出内存马 — 查看已注入的内存 shell

卸载内存马 — 移除指定内存 shell


🚀 高级功能

Shellcode 加载 — Base64 编码的 shellcode 注入执行

SOCKS5 代理 — 通过 webshell 隧道搭建 SOCKS5 代理，用于内网横向

端口扫描 — 通过隧道扫描内网主机端口

快速审计 — 一键安全审计（OS 版本、补丁、服务、端口、权限、安全产品）
