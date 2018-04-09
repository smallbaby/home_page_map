博客使用hexo构建。时间久了命令都快忘记了。此文档用来记录我的本机常用命令

- blog path: /Users/kaizhang/bigdata/blog/smallbaby.github.com
- 创建新文章 hexo new xxx
- 生成文章 hexo g
- push到git： hexo d
- 配置git
1. cat _config.xml 找到Deployment位置
```shell
# Deployment
## Docs: https://hexo.io/docs/deployment.html
deploy:
  type: git
  repo: https://github.com/smallbaby/smallbaby.github.io.git
  branch: master
  ```

官网：[hexo](https://hexo.io/zh-cn/docs/commands.html)
