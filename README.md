golang的http库web已经做的很好了，为什么需要web框架

1.路由支持不够优秀，譬如动态路由 hello/:name，hello/*等这种规则
2.鉴权（中间件）不够方便，需要在每个路由的 handler中实现
3.没有统一简化的 HTML机制等