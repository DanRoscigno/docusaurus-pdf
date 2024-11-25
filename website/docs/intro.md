---
sidebar_position: 1
---

# 存算一体

本教程涵盖了以下内容：

- 使用 Docker Compose 部署 StarRocks 存算一体集群。
- 导入数据集，并在导入过程中进行基本的数据转换。
- 查询分析数据。

本教程中使用的数据由 NYC OpenData 和 NOAA 的 National Centers for Environmental Information 提供。教程仅截取了数据集的部分字段。

---

## 前提条件

### Docker

- [安装 Docker](https://docs.docker.com/engine/install/)。
- 为 Docker 分配 4 GB RAM。
- 为 Docker 分配 10 GB 的空闲磁盘空间。

### SQL 客户端

您可以使用 Docker 环境中提供的 MySQL Client，也可以使用其他兼容 MySQL 的客户端，包括本教程中涉及的 DBeaver 和 MySQL Workbench。

### curl

`curl` 命令用于向 StarRocks 中导入数据以及下载数据集。您可以通过在终端运行 `curl` 或 `curl.exe` 来检查您的操作系统是否已安装 curl。如果未安装 curl，[请点击此处获取 curl](https://curl.se/dlwiz/?type=bin)。

---


Let's discover **Docusaurus in less than 5 minutes**.

## Getting Started

Get started by **creating a new site**.

Or **try Docusaurus immediately** with **[docusaurus.new](https://docusaurus.new)**.

### What you'll need

- [Node.js](https://nodejs.org/en/download/) version 18.0 or above:
  - When installing Node.js, you are recommended to check all checkboxes related to dependencies.

## Generate a new site

Generate a new Docusaurus site using the **classic template**.

The classic template will automatically be added to your project after you run the command:

```bash
npm init docusaurus@latest my-website classic
```

You can type this command into Command Prompt, Powershell, Terminal, or any other integrated terminal of your code editor.

The command also installs all necessary dependencies you need to run Docusaurus.

## Start your site

Run the development server:

```bash
cd my-website
npm run start
```

The `cd` command changes the directory you're working with. In order to work with your newly created Docusaurus site, you'll need to navigate the terminal there.

The `npm run start` command builds your website locally and serves it through a development server, ready for you to view at http://localhost:3000/.

Open `docs/intro.md` (this page) and edit some lines: the site **reloads automatically** and displays your changes.
