# EBanAutoTest
其实是发现行测可以刷但是gpt的准确度不够好（指不能100%）所以就自己写了个脚本，似乎是对于所有的易班学习都可以的，虽然没有测试，但是写的时候是往通用写的，所以取了这个名字

## 使用

`python main.py`

执行考试，如果已经训练好了

`python main.py train`

对于指定的考试进行训练以穷尽题库

`python main.py word`

导出docx文件方便分享

## 安装

### 安装webdriver

网上有很多安装webdriver的教程了，比如我使用的是chromedriver，自己搜教程安装一下就好了，如果使用其他浏览器，稍微更改代码即可

把`d = webdriver.Chrome()`更改为你自己的浏览器即可

### 安装python

我使用的是Python3.7.6

然后`pip install -r requirements.txt`即可
