# Hide-GoAgent
隐藏执行Goagent窗口


创建vbs脚本
```
Wscript.CreateObject("Wscript.Shell").run "D:\PROGRA~1\localproxy\python27.exe D:\PROGRA~1\localproxy\proxy.py",0
```
或者
```
Wscript.CreateObject("Wscript.Shell").run """D:\Program Files\localproxy\python27.exe"" ""D:\Program Files\localproxy\proxy.py""",0
```
