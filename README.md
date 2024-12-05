
roop的项目地址：https://github.com/s0md3v/roop

参考：https://github.com/dream80/roop_colab

roop使用的是【1.1.0】版本的

# 快速使用

- 安装Anaconda3
- 基于Anaconda3创建一个python3.10的环境
- 安装Git
- 安装ffmpeg

```markdown
我的操作系统版本是Ubuntu 18.04.4 LTS（带GPU会快一点），以上所说的环境请自行百度安装！
```

拉取项目

```bash
git clone git@github.com:VoidAndNullity/roop-jupyter.git
```

如果你还没有安装jupyter，请执行这个命令安装下

```bash
pip install jupyter
```

进入项目并打开roop.ipynb

```bash
cd roop

# 使用你的浏览器访问，然后点开roop.ipynb即可  如果无法访问请确认下8888端口是否开放
jupyter notebook --ip=0.0.0.0 --port=8888
```

走完上面这些步骤基本上就是准备好需要的图片和视频，然后在jupyter notebook内一路运行就好了，首次运行的时候会下载一些模型，在国内可能会下载很慢，我这边也把模型打包了，请往下看：

# 手动添加模型

百度网盘链接：

```
链接：https://pan.baidu.com/s/1pd_Mk3KuiesaowKnP0Rj4g 
提取码：2rfq 
```

------

inswapper_128.onnx放到roop项目当中的models目录中

------

你的路径和我的未必是一样的，这里我就只提供一个参考：

```bash
cd ~/.opennsfw2/weights
```

将网盘中对应这个路径的模型放入即可

------

你的路径和我的未必是一样的，这里我就只提供一个参考：

```bash
cd ~/.insightface/models

mkdir buffalo_l

cd buffalo_l
```

将网盘中对应这个路径的模型放入即可
