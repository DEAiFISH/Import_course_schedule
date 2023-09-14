# 课程表导入

1. **教程网址**

   > https://blog.xm.mk/posts/49/#预处理课表文件

2. **代码引用**

   > https://github.com/Xm798/ClasstableToIcalforNUAA

3. **课程网址**

   > https://jwxt.stbu.edu.cn/xtgl/login_slogin.html

4. **json数据**

```json
{
    "1": {
        "name": "1-2节",
        "startTime": "083000",
        "endTime": "101000"
    },
    "2": {
        "name": "3-4节",
        "startTime": "103000",
        "endTime": "121000"
    },
    "3": {
        "name": "5-6节",
        "startTime": "143000",
        "endTime": "161000"
    },
    "4": {
        "name": "7-8节",
        "startTime": "163000",
        "endTime": "181000"
    },
    "5": {
        "name": "9-10节",
        "startTime": "191000",
        "endTime": "205000"
    },
    "6": {
        "name": "9-11节",
        "startTime": "190000",
        "endTime": "211500"
    }
}
```

5. **TIPS**

   > **pip** uninstall xlds
   >
   > **pip** install xlrd==1.2.0