本项目为对[epcalc](https://github.com/gabgoh/epcalc)项目的中文翻译, 原项目在线版位于[http://gabgoh.github.io/COVID/index.html](http://gabgoh.github.io/COVID/index.html)

# SEIR 模型

SEIR 模型是一种常用的传染病模型，用来描述病毒如何在人群中传播。通常情况下，SEIR 模型用来描述一种传染病如何在群体中传播，并预测疫情的发展趋势。SEIR 模型假设人群中有四种不同的状态：易感者（S）、潜伏者（E）、感染者（I）和康复者（R）。

- 易感者（S）表示健康的人群，这些人尚未接触过病毒，因此对病毒没有免疫力。
- 潜伏者（E）表示已经接触过病毒但尚未发病的人群。
- 感染者（I）表示正在患病的人群，这些人会传播病毒给其他人。
- 康复者（R）表示已经康复的人群，这些人已经对病毒产生了免疫力，不会再被感染。

SEIR 模型还假设病毒传播受到群体免疫的限制。这意味着，随着更多的人接触病毒并产生免疫力，病毒在人群中的传播速度会减慢。通过模拟病毒在人群中的传播，SEIR 模型可以预测疫情的发展趋势，并为政府决策提供参考。

via https://chat.openai.com/chat

项目在线地址: https://yaozeyuan.online/seir-model/index.html

中文术语翻译参考

- 谷歌翻译
- [这份文档](http://web.stat.nankai.edu.cn/ZYRC/2MEChapters/MEChapt3.pdf)
- [这篇论文](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8800716/)

基础转化模型如下图

![基础转化模型](http://tva1.sinaimg.cn/large/007Yq4pTly1h8vrrj2ugaj30ae0503z7.jpg)

![image.png](http://tva1.sinaimg.cn/large/007Yq4pTly1h8vspvhf04j317z0wwe1x.jpg)
![image.png](http://tva1.sinaimg.cn/large/007Yq4pTly1h8vsqerl7bj317s0xrke0.jpg)
![image.png](http://tva1.sinaimg.cn/large/007Yq4pTly1h8vsqz3j5gj317q0ujgwt.jpg)
![image.png](http://tva1.sinaimg.cn/large/007Yq4pTly1h8vsrf8zj4j317o0tme52.jpg)

# 项目开发说明

初始化

```bash
yarn
```

项目启动

```bash
yarn dev
```

项目构建

```bash
yarn build
```

已配置 github-action, master 分支更新后即自动推送到 github-page 上
