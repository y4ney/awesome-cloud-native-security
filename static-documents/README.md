# 静态文档

> 🚥
>
> **一旦完成后内容基本不再变化的文档**。它们通常在首次创建和发布后不进行定期更新。

## 2024-08

46. 针对云环境的大规模勒索攻击
    
- 📅 日期：2024-08-15
- 🔗 链接：[Leaked Environment Variables Allow Large-Scale Extortion Operation of Cloud Environments](https://unit42.paloaltonetworks.com/large-scale-cloud-extortion-operation/)
- 💬 简介：这篇文章由Palo Alto Networks的Unit 42研究团队撰写，揭露了一个针对云环境的大规模勒索攻击。攻击者利用泄露的环境变量来访问敏感信息，并要求受害者支付赎金以避免数据泄露或服务中断。文章强调了安全配置云环境的重要性，建议企业定期审查和监控云基础设施的安全措施，包括访问控制和日志记录，以预防此类勒索攻击。文章还指出云安全漏洞是网络犯罪分子的一个主要攻击目标。

45. 深入探究 K8S Pod 安全策略与准入控制器：构建坚不可摧的容器安全防线

- 📅 日期：2024-08-04
- 🔗 链接：[深入探究 K8S Pod 安全策略与准入控制器：构建坚不可摧的容器安全防线（来自"WAKE UP技术"公众号）](https://mp.weixin.qq.com/s/HHGDJ_xtyNTcw0xTrWP7AA)

44. ArtiPACKED：GitHub Actions Artifacts

- 📅 日期：2024-08-13
- 🔗 链接：[ArtiPACKED：GitHub Actions Artifacts](https://unit42.paloaltonetworks.com/github-repo-artifacts-leak-tokens/)
- 💬 简介：这篇博客分析了在GitHub Actions中由于竞态条件导致的漏洞，该漏洞可以让攻击者通过上传恶意工件来窃取敏感信息，比如访问令牌(如GitHub令牌和第三方云服务凭据)。这种攻击方式被称为“ArtiPACKED”。文章详细描述了这一攻击的工作原理、潜在的危害以及如何防范此类攻击。

43. Grand Theft Actions: Abusing Self-Hosted GitHub Runners at Scale

- 📅 日期：2024-08
- 🔗 链接：<https://github.com/AdnaneKhan/ConferenceTalks/blob/main/DEFCON32_GrandTheftActions.pdf>
- 🔗 链接：Gato-X：<https://github.com/AdnaneKhan/Gato-X>
- 💬 简介：AdnanKhan和John Stawinski在DEF CON演讲中分享了他们一直在做的GitHub Action研究，他们已经发现了许多互联网规模的供应链安全漏洞，同时发布了Gato-X工具，以帮助其他安全研究人员大规模发现这些类型的漏洞。

42. CVE-2024-7646：Ingress-nginx注释验证绕过

- 📅 日期：2024-08-16
- 🔗 链接1：[K8s issue](https://github.com/kubernetes/kubernetes/issues/126744)
- 🔗 链接2：[CVE-2024-7646: Ingress-NGINX Annotation Validation Bypass – A Deep Dive](https://securityboulevard.com/2024/08/cve-2024-7646-ingress-nginx-annotation-validation-bypass-a-deep-dive/)
- 🔗 链接3：[CVE-2024-7646：Ingress-nginx注释验证绕过【高危】](https://mp.weixin.qq.com/s/heUTzB0clK0TP0bDGEunGw)

## 2024-07

41. 利用gitRepo volumes创建权限如何拿下K8s节点root权限

- 📅 日期：2024-07
- 🔗 链接1：[Sneaky write hook: git clone to root on k8s node](https://irsl.medium.com/sneaky-write-hook-git-clone-to-root-on-k8s-node-e38236205d54)
- 🔗 链接2：[Fun With GitRepo Volumes](https://raesene.github.io/blog/2024/07/10/Fun-With-GitRepo-Volumes/)
- 💬 简介：这两篇博客文章讨论了一个Kubernetes中未修补的安全问题，允许任何有权限创建gitRepo卷的用户以root用户身份在底层主机上执行代码。

40. Kubernetes 历史：它如何征服云原生编排

- 📅 日期：2024-07-25
- 🔗 链接：[Kubernetes History: How It Conquered Cloud Native Orchestration](https://www.aquasec.com/blog/kubernetes-history-how-it-conquered-cloud-native-orchestration/)


39. 过时的安全：为什么我们使用隔离虚拟机

- 📅 日期：2024-07-25
- 🔗 链接：[Unfashionably secure: why we use isolated VMs](https://blog.thinkst.com/2024/07/unfashionably-secure-why-we-use-isolated-vms.html)


38. 揭示AWS会话令牌的内部结构

- 📅 日期：2024-07-25
- 🔗 链接：[Revealing the Inner Structure of AWS Session Tokens](https://medium.com/@TalBeerySec/revealing-the-inner-structure-of-aws-session-tokens-a6c76469cba7)

37. 一份循序渐进的AWS渗透测试指南

- 📅 日期：2024-07-22
- 🔗 链接：[An Opinionated Ramp Up Guide to AWS Pentesting](https://awssecuritydigest.com/articles/opinionated-ramp-up-guide-to-aws-pentesting)
- 💬 简介：Lizzie Moratti提供了一份深入的AWS渗透测试指南，利用了[pwnedlabs.io](https://pwnedlabs.io/)靶场、Rich Mogull的[Cloud Security Lab a Week](https://slaw.securosis.com/)(每周云安全实验室)以及Scott Piper的[AWS Security Maturity Roadmap](https://summitroute.com/downloads/aws_security_maturity_roadmap-Summit_Route.pdf)（AWS安全成熟度路线图）等资源。Lizzie 提供了一些关于云渗透测试的热门观点，以及五阶段学习方法。


36. 容器逃逸：云环境中的逃逸技术(来自Palo Alto博客)

- 📅 日期：2024-07-18
- 💬 标题：Container Breakouts: Escape Techniques in Cloud Environments
- 🔗 链接：[Container Breakouts: Escape Techniques in Cloud Environments](https://unit42.paloaltonetworks.com/container-escape-techniques/)

35. 启用安全防护：使用 CDK for Terraform 实现基础设施即代码

- 📅 日期：2024-07-15
- 💬 标题：Enabling Security Guardrails: Infra as Code with CDK for Terraform
- 🔗 链接：[Enabling Security Guardrails: Infra as Code with CDK for Terraform](https://engineering.ziphq.com/enabling-security-guardrails-infra-as-code-with-cdk-for-terraform/)

34. 启动您的Kubernetes安全

- 📅 日期：2024-07-02
- 🔗 链接：[Kickstart Your Kubernetes Security](https://cloudnativenow.com/social-facebook/kickstart-your-kubernetes-security/)

## 2024-06

33. K8s日志指南

- 📅 日期：2024-06-01  
- 🔗 链接：[A Guide To Kubernetes Logs That Isn't A Vendor Pitch](https://grahamhelton.com/blog/k8slogs/)

32. 天翼云对象存储ZOS攻防

- 📅 日期：2024-06-26
- 🔗 链接：[天翼云对象存储ZOS攻防](https://zone.huoxian.cn/d/2916-zos)

31. 攻击者针对暴露的Docker API利用新技巧

- 📅 日期：2024-06-13
- 🔗 链接：[Attackers deploying new tactics in campaign targeting exposed Docker APIs](https://securitylabs.datadoghq.com/articles/attackers-deploying-new-tactics-in-campaign-targeting-exposed-docker-apis/)

## 2024-05

30. Docker 逃逸中被忽略的 pid namespace
- 📅 日期：2024-05-25
- 🔗 链接：[Docker 逃逸中被忽略的 pid namespace](https://tiangonglab.github.io/blog/tiangongarticle030/)

29. 实战-关于KEY泄露API接口利用

- 📅 日期：2024-05-11
- 🔗 链接：[实战-关于KEY泄露API接口利用](https://zone.huoxian.cn/d/2909-keyapi)

## 2024-04

28. 腾讯云对象存储COS（Cloud Object Storage）攻防

- 📅 日期：2024-04-15
- 🔗 链接：[腾讯云对象存储COS（Cloud Object Storage）攻防](https://zone.huoxian.cn/d/2903-coscloud-object-storage)

27. 京东云OSS攻防

- 📅 日期：2024-04-08
- 🔗 链接：[京东云OSS攻防](https://zone.huoxian.cn/d/2901-oss)

## 2024-02

26. TeamTNT攻击组织分析
- 📅 日期：2024-02-01
- 🔗 链接：[An analysis of a TeamTNT doppelgänger](https://securitylabs.datadoghq.com/articles/analysis-of-teamtnt-doppelganger/)

## 2023-11

25. 针对新手的Rego介绍

- 📅 日期：2023-11-03
- 🔗 链接：[Rego for beginners: Introduction to Rego](https://medium.com/@snyksec/rego-for-beginners-introduction-to-rego-0d293d52a654)

## 2023-10

24. MITRE 的 Container ATT&CK 攻防矩阵 v14.1-v15.1

- 📅 日期：2023-10-31～至今
- 🔗 链接：[MITRE 的 Container ATT&CK 攻防矩阵 v14.1-v15.1](https://attack.mitre.org/matrices/enterprise/containers/)

## 2023-04

23. MITRE 的 Container ATT&CK 攻防矩阵 v13.1

- 📅 日期：2023-04-25
- 🔗 链接：[MITRE 的 Container ATT&CK 攻防矩阵 v13.1](https://attack.mitre.org/versions/v13/matrices/enterprise/containers/)

22. 容器镜像的妙用——绕过漏洞扫描程序

- 📅 日期：2023-04-22
- 🔗 链接：[Fun with container images - Bypassing vulnerability scanners](https://raesene.github.io/blog/2023/04/22/Fun-with-container-images-Bypassing-vulnerability-scanners/)

## 2022-09

21. NSA 需要强大的 Kubernetes 身份验证和授权

- 📅 日期：2022-09-12
- 🔗 链接：[NSA Wants Strong Kubernetes Authentication and Authorization](https://cloudnativenow.com/features/nsa-wants-strong-kubernetes-authentication-and-authorization/)

## 2022-10

20. MITRE 的 Container ATT&CK 攻防矩阵 v12.1

- 📅 日期：2022-10-25
- 🔗 链接：[MITRE 的 Container ATT&CK 攻防矩阵 v12.1](https://attack.mitre.org/versions/v12/matrices/enterprise/containers/)

## 2022-07

19. 攻击者能够迅速利用著名的零日漏洞：2022年Unit 42事件响应报告见解

- 📅 日期：2022-10-25
- 🔗 链接：[攻击者能够迅速利用著名的零日漏洞：2022年Unit 42事件响应报告见解](https://unit42.paloaltonetworks.com/incident-response-report/)

## 2022-04

18. MITRE 的 Container ATT&CK 攻防矩阵 v11.3

- 📅 日期：2022-04-25
- 🔗 链接：[MITRE 的 Container ATT&CK 攻防矩阵 v11.3](https://attack.mitre.org/versions/v11/matrices/enterprise/containers/)

## 2021-11

17. 云原生安全：基于容器ATT&CK矩阵模拟攻防对抗的思考

- 📅 日期：2021-11-01
- 🔗 链接：[云原生安全：基于容器ATT&CK矩阵模拟攻防对抗的思考](https://www.freebuf.com/articles/security-management/303010.html)

## 2021-10

16. MITRE 的 Container ATT&CK 攻防矩阵 v10.1

- 📅 日期：2021-10-21
- 🔗 链接：[MITRE 的 Container ATT&CK 攻防矩阵 v10.1](https://attack.mitre.org/versions/v10/matrices/enterprise/containers/)

## 2021-09

15. 腾讯云鼎实验室的云安全攻防矩阵

- 📅 日期：2021-09-26
- 🔗 链接：[云安全攻防矩阵](https://cloudsec.tencent.com/home/)

## 2021-08

14. 青藤的 Kubernetes ATT&CK 攻防矩阵

- 📅 日期：2021-08-25
- 🔗 链接：[最佳实践：发布国内首个K8S ATT&CK攻防矩阵](https://mp.weixin.qq.com/s/-FTJRl1ZK2Etgq7KO17r7w)

## 2021-06

13. 如何设定切实可行的时间框架来修复安全漏洞

- 📅 日期：2021-06-23
- 🔗 链接：[How to Set Practical Time Frames to Remedy Security Vulnerabilities](https://www.gartner.com/smarterwithgartner/how-to-set-practical-time-frames-to-remedy-security-vulnerabilities)

## 2021-05

12. Metarget：云原生攻防靶场开源啦！

- 📅 日期：2021-05-10
- 🔗 链接：[Metarget：云原生攻防靶场开源啦！](https://mp.weixin.qq.com/s?__biz=MzIyODYzNTU2OA==&mid=2247489415&idx=1&sn=4aea7b7ecff51710c79037ab07a889bc)

## 2021-04

11. MITRE 的 Container ATT&CK 攻防矩阵 v9.0

- 📅 日期：2021-04-29
- 🔗 链接：[MITRE 的 Container ATT&CK 攻防矩阵 v9.0](https://attack.mitre.org/versions/v9/matrices/enterprise/containers/)

## 2021-03

10. 微软的 Kubernetes 威胁矩阵（二）

- 📅 日期：2021-03-23
- 🔗 链接：[Secure containerized environments with updated threat matrix for Kubernetes](https://www.microsoft.com/en-us/security/blog/2021/03/23/secure-containerized-environments-with-updated-threat-matrix-for-kubernetes/)

9. 红蓝对抗中的云原生漏洞挖掘及利用实录

- 📅 日期：2021-03-02
- 🔗 链接：[红蓝对抗中的云原生漏洞挖掘及利用实录](https://mp.weixin.qq.com/s/Aq8RrH34PTkmF8lKzdY38g)

## 2021-01

8. 伸手党的容器镜像加固流程

- 📅 日期：2021-01-06
- 🔗 链接：[伸手党的容器镜像加固流程](https://blog.fleeto.us/post/harden-docker-image-flow-chart/)

## 2020-10

7. 微软的 Kubernetes 威胁矩阵缺失的内容

- 📅 日期：2020-10-26
- 🔗 链接：[Microsoft's Kubernetes Threat Matrix: Here's What's Missing](https://www.darkreading.com/threat-intelligence/microsoft-s-kubernetes-threat-matrix-here-s-what-s-missing)

## 2020-06

6. 云原生环境渗透相关工具考察

- 📅 日期：2020-06-20
- 🔗 链接：[云原生环境渗透相关工具考察](https://blog.wohin.me/posts/cloud-native-pentest-tools/)

5. 阿里云的云上容器 ATT&CK 攻防矩阵

- 📅 日期：2020-06-18
- 🔗 链接：[国内首个云上容器ATT&CK攻防矩阵发布，阿里云助力企业容器化安全落地](https://developer.aliyun.com/article/765449)

## 2020-04

4. 微软的 Kubernetes 威胁矩阵（一）

- 📅 日期：2020-04-02
- 🔗 链接：[Threat matrix for Kubernetes](https://www.microsoft.com/en-us/security/blog/2020/04/02/attack-matrix-kubernetes/)

## 2020-02

3. 深入研究现实世界的Kubernetes威胁

- 📅 日期：2020-02-12
- 🔗 链接：[Deep Dive into Real-World Kubernetes Threats](https://research.nccgroup.com/2020/02/12/command-and-kubectl-talk-follow-up/)

## 2019-05

2. 容器安全：检查容器环境的潜在威胁

- 📅 日期：2019-05-14
- 🔗 链接：[Container Security: Examining Potential Threats to the Container Environment](https://www.trendmicro.com/vinfo/us/security/news/security-technology/container-security-examining-potential-threats-to-the-container-environment)

1. Falco 提供的针对容器运行时安全的 MITRE ATT&CK 框架

- 📅 日期：2019-05-10
- 🔗 链接：[MITRE ATT&CK framework for container runtime security with Falco](https://sysdig.com/blog/mitre-attck-framework-for-container-runtime-security-with-sysdig-falco/)
