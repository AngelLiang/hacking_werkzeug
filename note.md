# 学习笔记

werkzeug 的路由是在 routing.py 文件里，主要用到了以下知识点

- HTTP组成（shceme、domain、script、method等）
- 静态URL和动态URL
- 正则表达式：用于解析动态URL
- 类的继承等
- 工厂方法模式，用于构建Rule（`class RuleFactory`）
- 适配器模式，用于实现MapAdapter（`class MapAdapter`）
- WSGI的environ
