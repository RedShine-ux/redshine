# java基础重造

## 基本数据类型

```java
double b1 = 0.2;
double b2 = 0.2D;
double b3 = 0.2d;
float f1 = 0.2F;
float f2 = 0.2f;
long l1 = 12
long l2 = 12l
long l3 = 12L
```

以上赋值都是正确的

ps:  浮点数默认数据类型是double，float f = 0.2是错误的；

## 编码

ASCII  字母、数字、特殊字符128个，1byte

gbk 中文、日文、韩文  2byte

unicode 2byte

utf-8  数字、字母1byte  汉字3byte

## Math重造

Math.randow() 的范围是[0, 1), 返回值类型是double; Random 与 前面一样

## 异常

编译时异常

FileNotFoundException

IOException  这个[异常类](https://so.csdn.net/so/search?q=异常类&spm=1001.2101.3001.7020)是一个大的异常类 下面有很多子类 read() 在读的时候 文件可能不能读

ParseException  格式不正确

ClassNotFoundException
SQLException [SQL数据库](https://so.csdn.net/so/search?q=SQL数据库&spm=1001.2101.3001.7020)异常
IllegaArguementException
SocketException Socket异常
MalformedURLException URL格式错误异常

## 时间

Date、Calendar

Calendar c = Calendar.getInstance()



格式化时间  SimpleDateFormat  有parse（）与format（）方法

## 多线程

















