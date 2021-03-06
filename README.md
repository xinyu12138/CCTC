# CCTC - Classical Chinese Translation Corpus

[![License](https://img.shields.io/github/license/scagin/cctc)](https://github.com/Scagin/CCTC/blob/master/LICENSE)
![Stars](https://img.shields.io/github/stars/scagin/cctc)
![Forks](https://img.shields.io/github/forks/scagin/cctc)


[English document](./README.EN.md)

文言文翻译、古文翻译 语料数据集。(构建中)

## 数据说明

目前已整理的文言文翻译数据：

- 《史记》（29篇）
- 《论语》（20篇全）
- 《中庸》（33章全）

数据集格式

```json
[
    {
        "title": "",
        "contents": [
            {
                "source": "",
                "target": ""
            },
            {
                "source": "",
                "target": ""
            },
        ]
    }
]
```

数据集统计

|    |样本数|最大长度|最小长度|长度平均值|长度中位数|长度标准差|
|----|:---:|:------:|:-----:|:-------:|:-------:|:-------:|
|原文|7841  |180    |1      |17.67    |15.0     |13.54    |
|译文|7841  |280    |2      |29.20    |24.0     |23.28    |

## 贡献

- 欢迎有兴趣的朋友为此项目添砖加瓦，奉献自己的一份力。

- 如果您有部分整理好的文言文翻译语料，并且不介意将它开源的话，可以通过直接提交PR的形式进行贡献。

- 如果您认为该项目很有价值，并且愿意支持我不断完善该项目的话，您也可以通过「[支付宝](./static/alipay.jpg)」或者「[微信赞赏码](./static/wechat.jpg)」进行打赏赞助（备注留下您的邮箱）

## 引用

如果您希望能在您的研究中使用该数据集，请注明数据集的出处，https://github.com/scagin/cctc

如果您希望将该数据集用于训练商业算法模型，或其他用途，都是允许的。该开源数据集采用[MIT协议](.LICENSE)，一切声明都在协议当中。

## 联系方式

- 邮箱：406493851@qq.com

- QQ：406493851
