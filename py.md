## venv include win and redhat

虚拟环境之间互相隔离，虚拟环境与OS自带的Python解释器/库也隔离。

```python
python -m venv ENV_DIR # os default py version
python3.7 -m venv ENV_DIR # specific py version

.\ENV_DIR\Scripts\activate # win
source ENV_DIR/bin/activate # linux/mac

deactivate


python3 -m pip install --upgrade pip
python3 -m pip --version
sudo yum install python3-pip

python3 -m pip search xxx
python3 -m pip install xxx

```


[Python Paramiko库：SSH远程连接与文件传输实战指南](https://blog.csdn.net/wuShiJingZuo/article/details/134924451)


