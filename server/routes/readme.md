
# koa-router获取参数
 
## 使用 ctx.request.body或者 ctx.request.fields取得post表单参数 
## 使用 ctx.query取得路径查询参数    url:  /a/b?x=1&y=2
## 使用 ctx.params取得路径参数       url:'/employee/:pageSize/:pageIndex'

# resultful 常识
>1.GET： 向特定资源发出请求，并返回资源主体。

>2.POST：向指定资源提交数据处理请求，数据包含在请求中，可以修改资源。 

>3.PUT： 向指定资源位置上传最新内容，可以新建或修改资源。

>4.DELETE： 请求服务器删除Request-URI所标识的资源。

>5.OPTIONS： 返回服务器针对特定资源所支持的HTTP请求方法，也可利用向Web服务器发送'*'的请求来测试服务器的功能性。

>6.HEAD：向服务器索要与GET请求相一致的响应，只不过响应体不会被返回。该方法可以在不必传输整个响应内容的情况下，就能获取包含在响应消息头中的元信息。

>7.TRACE： 回显服务器收到的请求，主要用于测试或诊断。