使用了jade模板引擎，实现了分布试图以及模块化。

使用了百度富文本，解决了上传图片路劲的BUG。
但是不能使用图片管理遍历子目录，有待解决……

今天使用了mongoose 连通了数据库，总算这个应用不生成伪数据了。
实现了数据库的添加与查询，有待实现复杂的查询以及删除和修改。

对代码进行调整，更符合MVC结构

/*
:用以修改百度富文本上传路径 以日期分类  
var date = new Date();
          var datenow = date.getFullYear()+'-'+(date.getMonth()+1)+'-'+date.getDay();
          var dest = path.join(static_url,datenow, name);
  */