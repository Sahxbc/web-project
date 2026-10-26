# 仓库消耗品管理系统（报废管理模块）

软件工程课程项目：仓库消耗品管理系统，包含前端（Vue）、后端（Java Spring Boot）与数据库脚本。

## 技术栈
- 后端：Java、Spring Boot
- 前端：Vue.js、Vuex、Vue Router
- 数据库：MySQL

## 目录结构
- `后端代码_frame/`：Java Spring Boot 后端服务，实现报废申请、审核、处理等业务接口
- `前端代码_Web_frame/`：Vue 前端工程，对接后端接口完成数据展示与业务操作
- `数据库脚本/`：MySQL 建库建表脚本

## 运行说明
1. 导入数据库脚本 `crush_database.sql` 到 MySQL
2. 启动后端：进入 `后端代码_frame`，运行 `mvn spring-boot:run`
3. 启动前端：进入 `前端代码_Web_frame`，`npm install` 后 `npm run serve`
