# 学习如何使用docker 来打包/构建你的应用程序

## 1. 学习完本Issue 提供的文档, 你至少应该要能回答一下问题:
1. Docker是什么? 用Docker 有什么好处? 以及它的基本工作原理
2. 什么是Docker Image?
3. 什么是Docker container?
4. 学习如何使用Docker来打包/构建你的应用程序
5. 编写Dockerfile的最佳实践有哪些?
6. 如何在本地测试Docker Image/Container?
7. .dockerignore 是干什么的?

## 2. 任务
- [ ] 使用Dockerfile 来构建打包应用.
- [ ] 在安装依赖时, 通过优化Dockerfile层级, 来利用分层缓存机制, 从而更快的构建新的Docker Image.
- [ ] 使用非root 用户运行App程序.
- [ ] 给基础镜像加上digest指纹.

## 3. 学习路径
你可以依据这个学习路径, 从零开始逐渐深入对Docker的探索.
### 基础
1. [Docker — 从入门到实践](https://yeasy.gitbooks.io/docker_practice/content/) (预计30小时)

### 进阶
1. [Best practices for writing Dockerfiles](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/)

## 4. 事例 & 资源
- [Dockerfile reference](https://docs.docker.com/engine/reference/builder/)
