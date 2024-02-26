# 216telescope

b站：[216望远镜光谱数据处理教程](https://www.bilibili.com/video/BV1o24y1p77a/?spm_id_from=333.999.0.0&vd_source=1f85b66aea0aa541bef3c423adf160b3)

环境要求：
```shell
pip install laspec
pip install pyraf
pip install lightkurve==1.11.3
pip install -U git+git://github.com/hypergravity/songcn
```

前人的肩膀：
```shell
git clone https://github.com/lidihei/pyrafspec.git
cd pyrafspec
pip install .
rm -rf build pyrafspec.egg-info

git clone https://github.com/hypergravity/bfosc.git
```

服务器数据下载：
```shell
scp -r sdb216@10.3.10.45:/home/sdb216/BHBdata/216BFOSC_ORIGINAL/BHB_216/20240105_bfosc/ /Users/sara/PycharmProjects/216telescope/data/
```

服务器运行程序报错：
![img.png](img.png)
