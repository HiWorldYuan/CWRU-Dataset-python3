# CWRU-Dataset-python3
## 资料整理
## 1.引用自https://blog.csdn.net/tourior/article/details/78331280
基于python3的使用并细微修改，对比如下：
原：
    def _download(self, fpath, link):
        print("Downloading to: '{}'".format(fpath))
        urllib.URLopener().retrieve(link, fpath)
修改后：
    def _download(self, fpath, link):
        print("Downloading to: '{}'".format(fpath))
        urllib.request.urlretrieve(link, fpath)
        
## 2.使用细节见安装指南


