### **npc**

1. 项目目录
   
    * 前端资源放置到统一位置，此前以约定
    * 所有页面编写的js资源都形成js文件存放在相应的js目录下
2. 引用规则
    * css文件一律放置在head头中，其他部分不允许引用css
    ```
        <link rel="stylesheet" href="">
    ```
    * js文件一律放置在body闭合标签之前
    ```
      <script charset="utf-8" src=""></script>
    ```
    * 所有html标签要小写，js变量命名要使用驼峰命名法
    **Good**
    ```
     <body></body>
     ```
    **Bad**
    ```
      <BODY></BODY>
    ```
3. css文件class讲解
    * 遮罩效果
    ```
    <div class="nlist-mask"></div>
    ```
    *  面包屑
    ```
      <ul class="npc-breadcrumb">
        <li>您的位置:</li>
        <li><a href="#"></a></li>
        <li><a href="#">建议管理</a></li>
    </ul>
    ```
   > npc-breadcrumb 表示面包屑
   
   *  tab页下的切换按钮
   ```
     <span class="npc-tabBtn allSubBtn" id="allSubBtn"></span>
    ```
    > npc-tabBtn表示它是一个tab标签页下的按钮 allSubBtn表示的意思是所有正式提交，类比的还有reportBtn 表示生成报表，excelBtn表示导出数据,allEndBtn表示所有结束提交的
4. 命名规则
5. 简单调试技巧
