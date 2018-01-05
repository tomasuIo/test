# solutions

1.  Font creator 输出字体时内存溢出 :   打开的标签页太多

    ​



2.  Apollo 无法创建实例:  需要配置JAVA_HOME环境变量Apollo 启动生成

   的实例服务找不到路径: 需要配置APOLLO_HOME环境变量:  
>http://doc.okbase.net/similar/archive/192390.html



3.  Android studio 安装应用程序报错 :  installation failed with message failed 

    to finalize session:INSTALL_FAILED_INVALID_APK:    关闭 instant run

   

4.  android sdk manager 配置服务器：ip：203.208.43.88 port:80  

   http://ping.chinaz.com/ 上找g.cn



5.  android studio recyclerView包依赖报错，看看版本号后是否有后缀，如果有则删除。

    ​



6.  android 无法接收到广播：intentFilter.addAction("xxxxxxxxx"),字符串写错了，而编译器没有报错。





7.  文件处理时闪退，line = reader.readline().toString()!=null应该去掉

     toString(),不然就会恒为true。

   

8.  数据库onUpgrade()函数执行时，程序崩了，错误原因：

     db.execSQL("drop if exist table book");       应该为exists！而不是

     exist。。。。数据库操作会引起程序崩溃！

   

9.   java编写算法错误，导致读取xml文件的不正确

   

10.  汇编的结尾要返回Dos不然会导致很多未定义的行为




11.  jump语句跳转的代码段不需要ret



12.  

    > huzehao666@DESKTOP-Q669E4T MINGW64 /g/edk/AppPkg/Applications/final (master)
    > $ git commit -m "90%"
    >
    > *** Please tell me who you are.
    >
    > Run
    >
    >   git config --global user.email "you@example.com"
    >   git config --global user.name "Your Name"
    >
    > to set your account's default identity.
    > Omit --global to set the identity only in this repository.
    >
    > fatal: unable to auto-detect email address (got 'huzehao666@DESKTOP-Q669E4T.(ne)')
    >
    > huzehao666@DESKTOP-Q669E4T MINGW64 /g/edk/AppPkg/Applications/final (master)
    > $ git config --global user.email "592634894@qq.com
    > > "
    > > error: could not lock config file G:/edk/AppPkg/Applications/final/%HOMEDRIVE%OMEPATH%/.gitconfig: No such file or directory
    >
    > huzehao666@DESKTOP-Q669E4T MINGW64 /g/edk/AppPkg/Applications/final (master)
    > $

    :