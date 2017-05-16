常见命令
====

将wsdl（xml）文件编译为可执行文件：
wsimport -d . WeatherWS.xml -Xnocompile


将源文件打包为war包：
mvn package -Dmaven.test.skip=true


创建一个maven的Project：
mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app
