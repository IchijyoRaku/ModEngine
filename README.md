# 只狼mod引擎 /sekiro mod engine
简单的修改版，增加了多dll加载功能，现在改mod引擎的配置文件就可以同时加载多个dll，不用再靠原来mod的链式加载

示例：
```ini
[misc]
loadPlugins = [plugins\\1.dll, 2.dll]
```
不过相对路径是双斜杠注意下
# credit
* [katalash](https://github.com/katalash)
* [LeoSpecial-VEH-Hook](https://github.com/hoangprod/LeoSpecial-VEH-Hook)