---
title: "创建GitHub Page极简教程"
date: 2025-07-29 10:00:00 +0800
categories: [jekyll, blog]
layout: post
---

创建一个自己GitHub名称一致的仓库, 初始化2个文件即可:

1. `index.md`
2. `_config.yml`

index.md 内容:  
```markdown
---
layout: home
---
```

_config.yml 内容:
```yaml
title: 我的博客
theme: minima
```

再创建一个文件夹 `_posts`, 所有的博客文章都放在这个文件夹下.
博客文章的格式如下:

```markdown
---
title: "我的第一篇博客文章"
date: 2025-07-29 10:00:00 +0800
categories: [jekyll, blog]
layout: post
---

这是我的第一篇博客文章。
```

提交GitHub仓库, 即可在 https://splendone.github.io 上看到自己的博客了.