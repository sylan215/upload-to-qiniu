# 使用说明

#### 1. 请先安装 qiniu 的依赖库：

```python
python -m pip install qiniu
```

#### 2. 修改绑定域名

修改代码中的 http://github.com 为自己在七牛云存储绑定的域名

#### 3. 带两个参数执行脚本

第一个参数是上传后的目录，第二个参数是文件在本地的地址，支持文件夹。

其中第一个参数的目录格式为：image/test/。

比如如下的命令:

```
upload_to_qiniu.py image/test/ d:\test.png
```

运行后，上传后的文件地址就类似：http://github.com/image/test/test.png 

PS：已使用 Python2.7 和 Python3.4 亲测有效，其他 Python 版本如果有异常，请反馈
