![Banner image](https://user-images.githubusercontent.com/10284570/173569848-c624317f-42b1-45a6-ab09-f0ea3c247648.png)

# n8n-nodes-notion-to-markdown

这是一个 n8n 社区节点。它允许你将 Notion 的页面内容转换为 Markdown 格式。

Notion 是一个强大的笔记和知识管理工具，这个节点可以帮助你将 Notion 的页面内容转换为 Markdown 格式，方便内容的迁移和分享。

[n8n](https://n8n.io/) 是一个 [fair-code licensed](https://docs.n8n.io/reference/license/) 工作流自动化平台。

[安装](#安装)  
[操作](#操作)  
[认证](#认证)  
[兼容性](#兼容性)  
[使用](#使用)  
[资源](#资源)  

## 安装

在 n8n 中安装此节点：

1. 点击左下角个人信息旁边的三个点
2. 进入 Settings -> Community nodes
3. 点击 "Install a community node"
4. 输入 `n8n-nodes-notion-to-markdown`
5. 勾选后点击 Install

## 操作

* Convert Page to Markdown - 将 Notion 页面转换为 Markdown 格式

## 认证

你需要提供 Notion API 密钥来使用此节点。获取 API 密钥的步骤：

1. 访问 [Notion Developers](https://www.notion.so/my-integrations)
2. 点击 "New integration"
3. 填写集成名称和选择关联的工作区
4. 创建后复制 "Internal Integration Token"

## 兼容性

* 最低 n8n 版本要求：0.126.0
* 测试版本：0.126.0 及以上

## 使用

1. 在工作流中添加 "Notion to Markdown" 节点
2. 配置 Notion API 认证信息
3. 输入要转换的 Notion 页面 ID
4. 运行节点即可获取转换后的 Markdown 内容

## 资源

* [n8n 社区节点文档](https://docs.n8n.io/integrations/community-nodes/)
* [Notion API 文档](https://developers.notion.com/reference) 