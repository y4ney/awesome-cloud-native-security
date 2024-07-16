# 开源工具

12. GCPwn

- 🔗 链接：<https://github.com/NetSPI/gcpwn>
- 💬 简介：一个针对Google Cloud Platform (GCP) 的渗透测试框架，旨在帮助用户学习和利用GCP的安全特性，同时也为渗透测试人员和安全研究人员提供便利。用Python实现的类似于针对AWS的Pacu框架，专门为GCP设计。包括一些核心服务（云存储、云功能、云计算、IAM）的枚举模块以及大量漏洞利用模块的整合，其中许多模块都基于Rhino Security目前[公开的GCP漏洞利用存储库](https://github.com/RhinoSecurityLabs/GCP-IAM-Privilege-Escalation/tree/master)。是为 GCP 渗透测试人员/红队/研究人员制作一个最新的、维护良好的枚举和漏洞利用工具集，通过允许普通用户制作自己的模块并轻松与整体框架结合，降低学习 GCP 的门槛。
- 🎙️ 作者视频：来自fwd:cloudsec 2024会议[GCPwn：GCP 的渗透测试工具 - Scott Weston](https://www.youtube.com/watch?v=opvv9h3Qe0s)

11.   KubeHound

- 🔗 链接：<https://github.com/DataDog/KubeHound>
- 💬 简介：KubeHound是一款用于动态分析Kubernetes集群安全风险的工具，通过计算集群中各类资源配置与访问关系绘制潜在的攻击路径。KubeHound的优点在于使用图数据库，数据成果以集群资源为顶点(Vertex)，以攻击类型为边(Edge)，使用Gremlin数据库查询语言搜索攻击链路。
- 🎙️ 作者视频：来自SO-CON 2024会议[KubeHound and Beyond - Jeremy Fox]<https://youtu.be/pdCcJ-Kenf8?si=JyFUtRfJfFU2cDAP>
- 🔖使用案例：<https://mp.weixin.qq.com/s/sQ8brkm6D5DDTlUdaI41yw>

10. Stratus Red Team

- 🔗 链接：<https://github.com/DataDog/stratus-red-team>
- 💬 简介：Stratus Red Team是专门针对云环境设计的攻击模拟工具。它允许用户以一种细粒度和自包含的方式模拟攻击性攻击技术，可以被视为云环境中的"[Atomic Red Team™]。旨在帮助安全团队通过模拟攻击来测试和提高他们的云安全防御能力。通过这种方式，团队可以更好地了解潜在的攻击路径，并开发出更有效的防御策略。

9. Netfetch

- 🔗 链接：<https://github.com/deggja/netfetch>
- 💬 简介：该工具可以扫描 Kubernetes 集群以识别没有网络策略的 Pod，支持 Kubernetes 和 Cilium 网络策略。它也提供了可视化DashBoard来可以交互式更改网络策略和 Pod，在缺少策略的地方创建默认拒绝网络策略，并根据现有工作负载提供建议。

8. kubernetes-rbac-audit

- 🔗 链接：<https://github.com/cyberark/kubernetes-rbac-audit>
- 💬 简介：可以扫描Kubernetes RBAC以寻找有风险的角色的 Python 工具。

7. Sea Moon

- 🔗 链接：<https://github.com/DVKunion/SeaMoon>
- 💬 简介：月海基于 Serverless 的动态与无状态的特性，从网络层实现了一个基于 Serverless 的网络工具集，包括代理、转发、隧道等等常见网络功能； 同时在客户端集成了大量云厂商，实现快捷的一键式部署和跨厂商与平台操作。

6. Copacetic：容器镜像漏洞自动修复神器

- 🔗 链接：<https://github.com/project-copacetic/copacetic>
- 💬 简介：Copacetic（简称：copa）是微软工程师 Sertaç Özercan 使用 Go 开发的 CLI 工具，它基于 buildkit 的镜像构建能力和 Trivy 的漏洞扫描结果，可以自动修复容器镜像中的漏洞。

5. Trivy：容器镜像安全扫描器

- 🔗 链接：<https://github.com/aquasecurity/trivy>
- 💬 简介：可以扫描容器镜像、文件系统、代码仓库中的漏洞、错误配置、secret和license等安全风险。

4. BuildKit：制品构建工具

- 🔗 链接：<https://github.com/moby/buildkit>
- 💬 简介：BuildKit是一个工具包，用于转换源代码，以高效、富有表现力和可重复的方式构建制品。

3. trivy-db-to：转换 Trivy 漏洞库的格式

- 🔗 链接：<https://github.com/k1LoW/trivy-db-to>
- 💬 简介：将 Trivy 的漏洞库的格式从 Boltdb 转换为 MySQL、PostgreSQL 和 SQLite 的格式。

2. s3fs：S3 存储桶挂载工具

- 🔗 链接：<https://github.com/s3fs-fuse/s3fs-fuse>
- 💬 简介：s3fs 允许 Linux、macOS 和 FreeBSD 用户通过 FUSE（用户空间文件系统）将 S3 存储桶挂载成本地文件系统，使用户可以像操作本地文件系统一样操作存储桶。

1. k0otkit：以K8s的方式操纵K8s

- 🔗 链接：<https://github.com/Metarget/k0otkit>
- 💬 简介：k0otkit（Kubernetes+rootkit）是一种通用的后渗透技术，可用于针对Kubernetes集群的渗透。您可以以快速、隐蔽和连续的方式（反向外壳）操作目标Kubernetes集群中的所有节点。
