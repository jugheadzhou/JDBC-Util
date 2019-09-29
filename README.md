# JDBC-Util
封装jdbc小工具，复习jdbc原生操作.
jdbc包含了数据库的操作规范，自己并没有提供实现

整体连接流程：

Java程序——实现jdbc提供的对应的操作规范——通过连接驱动找到对应的数据库服务器——执行对应的数据库的操作语句

实际上就是：
java——connection——statement——mysql服务器——mysql.exe