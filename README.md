# PDF_to_Word
60行代码实现多线程PDF转Word

## 使用方法

* clone或下载项目到本地
```python
git clone git@github.com:178200623/PDF_to_Word.git
```

* 进入项目目录，建立虚拟环境，并安装依赖

```python
cd pdf2word
pyvenv venv
source venv/bin/active
pip install -r requirements.txt
```

* 修改config.cfg文件，指定存放pdf和word文件的文件夹，以及同时工作的进程数
* 执行```python main.py```
