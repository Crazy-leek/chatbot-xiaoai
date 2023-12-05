# chatbot-xiaoai

- 本项目通过对10万语料库的训练+公开的推特数据，实现了聊天机器人+情绪检测，可以初步实现测试与聊天机器人聊天用户的情绪状况.
- 技术框架 ：Seq2seq框架，LSTM，Attation机制，Tensorflow2.0+Keras，Html+Vue，Ajax。
- 项目介绍 ：重点解决了文本预处理、模型构建和训练，以及网页设计与实现。通过改进的Seq2seq模型，实现了实时对话，通过带标签数据和分类模型训练抑郁模型，实现文本抑郁检测。

## 虚拟女友聊天机器人模型

* 本项目基于 青云语料库10万组对话 训练

## 项目运行

- 克隆项目
- 运行`chatbot2.py`

## 带GUI版运行

- 运行`server.py`,通过日志给出的网址进入，以此来访问该项目。

## Docker 命令一键运行
```bash
docker run -p 外部端口:8888 -t devmrc/chatbot-xiaoai:tag
```
## 注意

* 由于时间及人员限制，语料库及部分代码取自公开数据及AI大模型，最终效果只实现了虚拟女友最核心的对话情绪检测部分，对女友特有的特性并没有做进一步的微调，并且页面设计比较粗糙没有明确的用户需求倾向
* 仅供学习交流使用。