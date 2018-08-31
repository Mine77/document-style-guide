# 文档规范

## 各类型文档规范
* [GitHub Readme 规范](readme-structure.md)
* [API 文档规范](api-structure.md)
* [教程文档规范](tutorial-structure.md)

## 文档注意事项 
1. 如果某部分描述的内容依赖于其他文档的内容，如某个 API 的参数字段等，则建议连接到相应文档去，而不是在本地文档里重复描述一遍。这是基于文档实效性而做出的考虑：在使用了链接的情况下，如果被依赖的文档做出了更改，本地文档不需要实时作出相应的修改；若未使用链接，如果依赖文档作出修改，则需要相应的去修改本地文档，会影响实效性，同时增加不必要的工作量。  
例如：交易参数的具体说明请参考 [CITA 相关文档](https://docs.nervos.org/cita/#/rpc_guide/rpc?id=%E6%9E%84%E9%80%A0protobuf%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84)


## 文件名

文档的文件名不得含有空格。

文件名必须使用半角字符，不得使用全角字符。这也意味着，中文不能用于文件名。

```
错误： 名词解释.md

正确： glossary.md
```

文件名建议只使用小写字母，不使用大写字母。

```
错误：TroubleShooting.md

正确：troubleshooting.md 
```

为了醒目，某些说明文件的文件名，可以使用大写字母，比如`README`、`LICENSE`。

文件名包含多个单词时，单词之间建议使用半角的连词线（`-`）分隔。

```
不佳：advanced_usage.md

正确：advanced-usage.md
```

## 参考链接模版 (Reference Links)
中文版：
* [Cryptape](https://www.cryptape.com/) - 中国第一的信任创造技术公司
* [Nervos Foundation](https://www.nervos.org/) - 下一代加密经济基础设施
Next Generation of Infrastructure for Cryptoeconomics
* [Nervos Forums](https://forums.nervos.org) - Nervos 开发者的论坛

英文版：
* [Cryptape](https://www.cryptape.com/) - No.1 Trust-Building Technology Company in China
* [Nervos Foundation](https://www.nervos.org/) - Next Generation of Infrastructure for Cryptoeconomics
* [Nervos Forums](https://forums.nervos.org) - Forums for Nervos Developers

## 参考读物

- [Redux 手册](http://redux.js.org/index.html)
- [Atom 手册](http://flight-manual.atom.io/)