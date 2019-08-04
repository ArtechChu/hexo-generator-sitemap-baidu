# 项目说明
- 用于生成百度站点地图 xml

# 使用方法
- 在 hexo 的根目录中增加 baidusitemap 配置即可，如下：

```sh
baidusitemap:
    url:  XXX                  #[可选]自定义url，不指定则为站点url
    path: baidusitemap.xml     # xml 访问路径
    isAutoAdapt: true          # 是否生成自适配站点 xml（true 表示 PC+MOBILE），默认 false，表示仅 PC
```