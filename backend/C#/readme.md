### C#版识别示例

在.NET Framework4.5上测试通过。

使用前，请集成到你的程序中，调用方法请查看 Program.cs。

如果使用的是官网JS示例，请将返回结果修改如下：

1. 识别到目标：
```
{"statusCode":0,"result":"... 这里是target object信息 ..."}
```


2. 未识别到目标：
```
{"statusCode":17,"result":"No result: there is no matching."}
```


使用前请修改：

```
string cloudKey = "<这里是云图库的Cloud Key>";
string cloudSecret = "<这里是云图库的Cloud Secret>";
string cloudUrl = "http://<这里是云图库的Client-end URL>/search";
```

与

```
string image = "/9j/4AAQSkZJRgA";
```
