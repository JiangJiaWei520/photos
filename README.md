原地址：https://github.com/lawlite19/Blog-Back-Up

---

图片用于:https://doctording.github.io/

直接将原始图片，按照类似的"2018-05-01_图片名.jpg"格式定义好，然后运行如下命令，完成图片的剪裁，压缩和提交到repo仓库

```bash
$ python tool.py 
```

注意安装python PIL模块

hexo + gitbook 的data.json的写法如下：

```json
{"list": 
    [
        {
            "arr": {
                "link": [
                    "2018-05-01_hangzhou_01.jpg",
                    "2018-05-01_hangzhou_02.jpg",
                    "2018-05-01_hangzhou_03.jpg"
                ], 
                "text": [
                    "01", 
                    "02",
                    "03"
                ], 
                "month": 5, 
                "type": [
                    "image", 
                    "image",
                    "image"
                ], 
                "year": 2018
            },
            "date": "2018-05"
        }
    ]
}
```
