# JavaRestApiTomcat
This project shows how to depoly a java rest api using jersey and tomcat.
If you wish to use this code, you need to be careful with some thing
1. Put your servlet package name in <init-param> like this
    "<param-value>com.ibm.irl</param-value>"
2. To access the servelt url will be like this: http://localhost:port/context-root/rest/hello. Sometimes context-root is project name or as set in server.xml file under /path

