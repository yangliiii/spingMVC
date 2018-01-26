# SpringMVC

## 主要类

DispatcherServlet : 前端控制器，负责接收前段request请求，将请求转发给对应的处理组件。

HandlerMapping : 请求与方法之间的映射关系，url到controller映射的组件。

Controller : 处理请求，返回ModelAndView对象。

ModelAndView : 封装了Controller的处理结果及视图。

ViewResolver : 视图解析器

View : 返回视图

