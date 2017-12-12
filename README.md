 * 创建项目dynamic web project
 * 创建guestbook action空白类
 * 配置struts2相关, struts.xml, web.xml
 * 配置tomcat server，可以看到空白页(system.out.println确认被调用)
 * 添加list.jsp，在struts.xml添加action，在guestbookd类list方法，显示list.jsp模板内容
 
 **check point** 正确被调用

 * 添加submit方法以及配置action：接受用户提交的数据（message），加入arraylist，并保存到文件。

 **check point** 检查文件内容是否有变更

 * 添加list方法，读取文件，并在jsp中显示出来。