<p align="center">
  <img height="100px" src="./logo.png" />
</p>

# [Drupal](https://github.com/drupal/drupal)

Drupal是一个开源的内容管理系统(CMS)平台。

## 部署

本项目基于开源项目 [CloudBase Framework](https://github.com/Tencent/cloudbase-framework) 开发部署，支持一键云端部署

[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&appUrl=https%3A%2F%2Fgithub.com%2FTencent-Cloud-Plugins%2FTencentCloudBase-Drupal&branch=master)
### 配置
- `DRUPAL_DATABASE_HOST`：数据库地址
- `DRUPAL_DATABASE_NAME`：数据库名
- `DRUPAL_DATABASE_PORT_NUMBER`：数据库端口号
- `DRUPAL_DATABASE_USER`：数据库用户名
- `DRUPAL_DATABASE_PASSWORD`：数据库密码
- `DRUPAL_USERNAME`：管理员账户名
- `DRUPAL_PASSWORD`：管理员账户密码
- `PORT`：应用端口号

### 依赖

- CynosDB：使用 CynosDB 数据库存储数据
- CFS：使用 CFS 持久化存储数据

## 注意事项

