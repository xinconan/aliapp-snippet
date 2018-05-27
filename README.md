# aliapp-snippet

为VSCode提供[支付宝小程序](https://docs.alipay.com/mini/developer/getting-started) API语法支持及代码片段。

![](https://vsmarketplacebadge.apphb.com/version/xinconan.aliapp-snippet.svg)
![](https://vsmarketplacebadge.apphb.com/installs/xinconan.aliapp-snippet.svg)

> 2018-05-18 update：增加了 `axml` 的支持，直接使用支付宝开发者工具内置的扩展，并在其基础上增加了`template` 和 `block` 扩展。

## 安装
1. 在VSCode中，打开扩展（`Ctrl + Shift + X`），搜索 `aliapp-snippet`。
2. 点击 `install/安装`。

## 使用
输入关键词，然后回车。关键词部分大小写

### 代码示例
- my.a
```javascript
my.alert({
  title: '',
  content: '',
  buttonText: '确定',
  success: () => {
    
  },
})
```
- my.sl
```javascript
my.showLoading({
  content: '',
  delay: 0,
})
```
- more...

## TODO List
- [x] 导航栏
- [x] TabBar
- [x] 交互反馈
- [x] 下拉刷新
- [x] 联系人
- [x] 选择城市
- [x] 选择日期
- [ ] 动画
- [ ] 画布
- [ ] 地图
- [x] 键盘
- [x] 滚动
- [ ] 节点查询
- [x] 用户授权
- [x] 获取会员信息
- [x] 唤起支付
- [x] 代扣签约
- [x] 跳转支付宝卡包
- [ ] 会员开卡授权
- [x] 芝麻认证
- [ ] 信用借还
- [x] 文本风险识别
- [x] 小程序跳转
- [x] 图片
- [x] 缓存
- [ ] 文件
- [x] 位置
- [x] 网络
- [x] 设备
- [x] 扫码
- [ ] 蓝牙
- [x] 数据安全(rsa)
- [x] 分享
- [x] 自定义分析

## License
MIT

-----------------------------------------
**Enjoy!**
