# 论文整理工具合集

收集整理全球范围内与论文整理、文献管理相关的**开源软件**、**项目**和**免费工具**。

> 这个列表包含 {{ .Items | len }} 个工具

## 工具列表

| 工具名称 | 简介 | 特点 | 编辑 |
|---------|------|------|------|
{{ range .Items }}
| [{{ .Name }}]({{ .Website }}) | {{ .Description }} | {{ .Features }} | [编辑](items/{{ .Filename }}) |
{{ end }}

## 分类

### 本地文献管理
- Zotero
- Mendeley
- ...

### 云端协作
- EasyBib
- ...

### 浏览器扩展
- ...

### 相关链接
- [Awesome Bibliography Management](https://github.com/...)
- [Citations Management Tools](https://github.com/...)

## 许可证
MIT License
