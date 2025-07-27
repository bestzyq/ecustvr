# ecustvr

## 介绍
ECUSTVR俱乐部官方网站

## 仓库同步与部署说明

本项目采用多平台仓库同步机制，确保代码在不同平台的一致性和网站的自动部署：

### 仓库同步流程

- **主仓库**：
  - GitHub: [https://github.com/ECUSTVR/ecustvr.github.io](https://github.com/ECUSTVR/ecustvr.github.io)
  - CNB: [https://cnb.cool/ecustvr/ecustvr](https://cnb.cool/ecustvr/ecustvr)

- **同步机制**：
  - GitHub 与 CNB 仓库实现双向同步
  - CNB 自动推送至 Gitee 仓库：[https://gitee.com/ecustvr/ecustvr](https://gitee.com/ecustvr/ecustvr)

### 网站部署

- **自动部署**：Tencent EdgeOne Pages 服务会实时抓取 Gitee 仓库更新并自动部署网站
- **更新流程**：代码提交到任一主仓库后，将自动同步至其他平台并触发网站更新

> 注意：为保持同步一致性，建议选择 CNB 仓库进行代码提交，避免在多个平台同时修改相同文件
