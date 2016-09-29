# Docker

## Docker 是什么？

> Docker 是一种容器技术，它可以将应用和环境等进行打包，形成一个独立的，类似于 iOS 的 APP 形式的「应用」，这个应用可以直接被分发到任意一个支持 Docker 的环境中，通过简单的命令即可启动运行。Docker 是一种最流行的容器化实现方案。和虚拟化技术类似，它极大的方便了应用服务的部署；又与虚拟化技术不同，它以一种更轻量的方式实现了应用服务的打包。使用 Docker 可以让每个应用彼此相互隔离，在同一台机器上同时运行多个应用，不过他们彼此之间共享同一个操作系统。Docker 的优势在于，它可以在更细的粒度上进行资源的管理，也比虚拟化技术更加节约资源。

参考：[Docker 入门](http://docs.daocloud.io/faq/docker101)

## Docker 基础技术

- Linux Namespace [1](http://coolshell.cn/articles/17010.html) [2](http://coolshell.cn/articles/17029.html)
- [DeviceMapper](http://coolshell.cn/articles/17200.html)
- [AUFS](http://coolshell.cn/articles/17061.html)
- [Linux CGroup](http://coolshell.cn/articles/17049.html)

## 为什么容器技术将主宰世界？

将 Docker 容器类比集装箱。

为什么容器技术如此诱人？
- 资源独立、隔离
- 环境的一致性
- 轻量化
- Build Once, Run Everywhere

容器技术的必然发展趋势：
- 容器是一项伟大的变革，但它还不能在段时间内产生巨大收益
- 自动化成都将进一步提高，运维人员由劳动密集型逐渐转向知识密集型
- 容器技术标准
- 云计算平台的支持
- 使用容器的习惯逐渐形成
- 行业规模
- 应用在云计算平台间的无缝迁移

参考：[为什么容器技术将主宰世界](http://blog.csdn.net/gaoyingju/article/details/49616295)

## 如何学习 Docker？

- 了解 Docker 基本理念和实践方式
- 从实践从了解 Docker 的基本应用
- 掌握 Docker 的网络配置知识
- 掌握 Docker 性能监控管理知识
- 掌握基本的 Docker 项目实践
  + 构建 SSH 镜像
  + 构建 Python/PHP/MySQL/Java 等技术栈
  + 如何在公有云中部署 Docker
  + Dockerfile 的实际应用
- 学会构建 Docker 集群

参考：[Docker技术快速精通指南](http://www.dockerinfo.net/2443.html)
