---
categories: Elog-Notion
cover: 'https://prod-files-secure.s3.us-west-2.amazonaws.com/13a508a2-de5b-47bc-b05f-367d31c13e36/d9977190-9097-4d01-9bb0-a90af8d25731/%E5%B9%BD%E7%81%B5%E5%85%AC%E4%B8%BB2.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20231116%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20231116T135449Z&X-Amz-Expires=3600&X-Amz-Signature=1c2808ceb2d7340154cb96e1389d5fe97d211f6e37b06fd35f974ffe128cc922&X-Amz-SignedHeaders=host&x-id=GetObject'
tags:
  - notion
date: '2023/11/16 00:00:00'
permalink: notion-example/
title: Notion示例文章
updated: '2023/11/16 21:17:00'
---

# Notion-Markdown


[Notion示例文章源地址](https://1874.notion.site/Notion-0658ee89cadf4d0e9b6adfbb1d953c70)


## 行内样式


- **加粗**


_斜体_


<u>下划线</u>


删除线


行内代码 `const a = 123`


行内公式，在Vitepress会报错，不做演示


红色的文字


蓝色的文字背景


绿色的块背景


## Basic block（基本块）


## Notion示例文章的子页面

Notion示例文章的子页面


| 表格标题 | 备注              |
| ---- | --------------- |
| 测试1  | 啊大大             |
| 测试2  | `const a = 123` |

- 无序列表
1. 有序列表：事物按规律变化，也有一种不可避免的性质．这种性质就叫做**必然性**
	1. 事物的必然性，是事物本身的性质（我们反对宿命论的是其认为这一切是受神明的支配，而不是反对事物发展中存在的不可避免的性质的事实）
		1. 第三级别列表
		2. 第三级别列表
	2. 其决定于它自己本身发展的情况和周围的条件
		1. 第三级别列表
			1. 第三级别列表
<details>
<summary>折叠块：点击展开【一级】</summary>
<details>
<summary>点击展开【二级】</summary>
<details>
<summary>点击展开【三级】</summary>

内容文本


</details>


</details>


</details>


> 引用块


---


[link_to_page](f478ef37-c82a-41f1-b7a5-9c195b043831)


> 👏 标注文本：**Elog 0.4.0-beta.7 发布了！**  
> 开放式跨平台博客解决方案，随意组合写作平台和部署平台  
>   
> 帮助导航👇  
> ❓ [Elog能干什么](https://elog.1874.cool/notion/introduce)  
> 🚀 [快速开始](https://elog.1874.cool/notion/start)


## Media（媒体）


![cover.JPG](/images/10a91945736a3027f2854218fa71c659.JPG)


[bookmark](https://elog.1874.cool)


[46_1677164223.mp4](https://prod-files-secure.s3.us-west-2.amazonaws.com/13a508a2-de5b-47bc-b05f-367d31c13e36/5999649b-7796-46a0-abd4-2e17b7b607ab/46_1677164223.mp4?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20231116%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20231116T135451Z&X-Amz-Expires=3600&X-Amz-Signature=5667d133f280bfd1232b8a4838ec4e2060236c431a849926e2358ff093c03193&X-Amz-SignedHeaders=host&x-id=GetObject)


```python
pwd='123456'
print(f"password={pwd!r}")

## output:
#password='123456'
```


[example.txt](https://prod-files-secure.s3.us-west-2.amazonaws.com/13a508a2-de5b-47bc-b05f-367d31c13e36/753c8245-2aea-45de-8a5a-509c105f6236/example.txt?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20231116%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20231116T135451Z&X-Amz-Expires=3600&X-Amz-Signature=c14aeb19dc874b9a77323bc23544fd4cb7f99d4e0ab0f16e23b49ed4a2cf0d6e&X-Amz-SignedHeaders=host&x-id=GetObject)


## DataBase（数据库）


数据库


## AI block


API不支持，会报错`Block type ai_block is not supported via the API.`


## Advanced block（高级块）


$$
f\left(\left[\frac{1+\{x, y\}}{\left(\frac{x}{y}+\frac{y}{x}\right)(u+1)}+a\right]^{3 / 2}\right)\tag{行标}
$$


Notion示例文章的同步块


# 折叠一级标题


	## 折叠二级标题


		折叠内容


两列分栏（左）

- [ ] 左侧书写

两列分栏（右）

- [ ] 右侧书写

```mermaid
graph LR;
Mermaid思维导图-->思维导图
Mermaid思维导图-->研发
```


@Anonymous 


[Notion-Markdown](https://www.notion.so/f478ef37c82a41f1b7a59c195b043831) 


2023-04-26 


🚀🔥🐸


## Embeds（嵌入）


嵌入网页


[embed](https://elog.1874.cool)

