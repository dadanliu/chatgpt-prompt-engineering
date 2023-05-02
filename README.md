# fix openai timeout problem
https://www.cnblogs.com/ghj1976/p/diao-yongopenai-deapi-chu-xianrequest-timed-out-ch.html
https://github.com/zhayujie/chatgpt-on-wechat/issues/351

# switch to aliyun source to install dep
在 macOS 或 Linux 上，配置文件通常位于 ~/.pip/pip.conf。如果不存在，请创建一个名为 pip.conf 的新文件。
```bash
[global]
index-url = https://mirrors.aliyun.com/pypi/simple/
```
保存并关闭配置文件。现在，pip 命令将使用指定的镜像源进行安装。

# version
Python 3.10.8

# install
pip3 install -r requirements.txt

# create virtual env store local dep 
python3 -m venv venv

# order pizza chatbot
panel serve chatbot.py --show

