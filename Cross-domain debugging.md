## 前端与后台接口跨域联调

1. fiddler autoResponse 自动代理转发

   **问题：** set-cookie不能在后面使用
   
2. 使用 http-proxy自定义代理转发
3. 设置服务端Access-Control-Allow-Origin/ Access-Control-With-Credients 
   客户端： var  xmlHttp = new XMLHttpRequest(); xmlHttp.withCredients = true;
