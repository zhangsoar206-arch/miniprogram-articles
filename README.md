# 小程序文章库

这是小程序「知识库」的文章数据源。

## 目录结构

```
articles/       # 文章 JSON 文件
images/         # 图片资源
api/            # API 接口数据
└── articles.json   # 文章索引
```

## 文章格式

每篇文章是一个 JSON 文件，包含：
- `id`: 文章唯一ID
- `title`: 标题
- `content`: 内容（HTML格式）
- `category`: 分类
- `coverImage`: 封面图URL
- `createTime`: 创建时间
- `updateTime`: 更新时间

## 小程序接口

文章列表接口：
```
https://raw.githubusercontent.com/{owner}/{repo}/main/api/articles.json
```
