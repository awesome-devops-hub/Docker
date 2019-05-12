# 学习如何使用 docker-compose 来搭建开发环境

## 1. 前置课程
- [学习如何使用docker 来打包/构建你的应用程序](./01-dockerise.md)

## 2. 期望的收获
- 学到什么是 docker-compose, 以及为什么它会这么有用?
- 学到如何使用 docker-compose 搭建一个环境隔离的、快起快停的开发和测试环境

## 3. 任务
基于 ruby (TODO) 或者 Node.js (TODO) 项目, 使用docker-compose 创建一个可以用于本地开发/测试, 以及以后要用于CI 构建的沙盒环境.
- [ ] 创建一个 `docker-compose.yml` 文件
- [ ] 创建一个 `auto/dev-environment` 脚本, 用来进入开发环境
- [ ] 创建一个 `auto/test` 脚本, 用来跑测试

## 4. 学习路径
### 教程
1. [Docker — 从入门到实践#docker-compose](https://yeasy.gitbooks.io/docker_practice/compose/)
2. [Bash scripts](https://www.taniarascia.com/how-to-create-and-use-bash-scripts/)


### 文档
1. [docker-compose references](https://docs.docker.com/compose/compose-file/)
2. [Bash flags](https://www.tldp.org/LDP/abs/html/options.html)
3. [Bash translator](https://explainshell.com/)
4. [Bash Traps](http://tldp.org/LDP/Bash-Beginners-Guide/html/sect_12_02.html)
5. [代码事例: docker-compose.yml]()(TODO)
6. [代码事例: auto scripts]()(TODO)
7. [代码事例: dev-environemnt]()(TODO)
