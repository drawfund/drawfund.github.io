# drawio-PWA-file-handling.md

Windows平台，快速打开drawio文件的工具，使用浏览器。对于小文件，无需使用drawio-desktop。

**安装Drawio**

【1】下载[Tomcat10](https://dlcdn.apache.org/tomcat/tomcat-10/v10.0.10/bin/apache-tomcat-10.0.10.exe)

【2】安装Tomcat10

【3】下载[draw.war](https://github.com/jgraph/drawio/releases)

【4】复制draw.war到<u>C:\Program Files\Apache Software Foundation\Tomcat 10.0\webapps</u>

【5】启动Tomcat10，或设置开机自动启动Tomcat10。

【6】Chrome浏览器输入http://127.0.0.1/draw/

**开启File Handling API**

【1】Chrome浏览器输入<u>chrome://flags/</u>

【2】找到File Handling API并Enabled开启。

【3】下载<u>drawio-PWA-file-handling.7z</u>（内测中，暂不提供下载）

【4】解压复制内容到<u>C:\Program Files\Apache Software Foundation\Tomcat 10.0\webapps\drawio-file-handling</u>

【5】浏览器打开http://127.0.0.1/drawio-file-handling/

【6】浏览器菜单项➝More Tools➝Create shortcuts...➝Create（可以勾选Open as window）

【7】桌面会出现图标，以后可以双击drawio文件，直接用浏览器打开。

