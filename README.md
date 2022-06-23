一言

> 前言：接口无任何限制，相关数据已经开源，如果不放心可以自行编写服务。

[服务站点](https://hitokoto.suraimu.org/)

[开源数据地址](https://github.com/suraimu-org/hitokoto)

[github 展示地址](https://suraimu-org.github.io/hitokoto.io/)


[QQ交流群: 592855459](https://jq.qq.com/?_wv=1027&k=V9EkDRJh)




## 请求公共参数

| 参数名称 | 参数类型 | 是否必须 | 参数描述 |
| --- | --- | --- | --- |
| Accept | string | 是 | application/json 和 text/plain |


## 数据结构

| 字段 | 类型 | 描述 | 示例 |
| --- | --- | --- | --- |
| content | string | 内容 | 人的感受，真的很复杂很纤细，没人会把所有想法说出口，时而矛盾，时而撒谎。 |
| author | string | 作者名(可能为空) | 薇尔莉特 |
| artwork | string | 作品名（可能为空） | 紫罗兰永恒花园 |

```json
{
	"content": "自认为为他人好而做的事情，并不一定正确。",
	"author": "伊雷娜",
	"artwork": "魔女之旅"
}
```
