# uni.webview.js
使用uni-app开发的H5网页，嵌套在uni-app项目中使用，互相通信，兼容小程序

## 使用示例
``` js
1、下载js库，包含 jweixin_1.4.0.js 和 uni.webview.js

2、在main.js中引入
const tui = require("@/static/js/uni.webview.js")
Vue.prototype.tui = tui

3、在页面中使用跳转api
this.tui.navigateTo({
	url: url
})			
				
this.tui.switchTab({
	url: "/pages/index/index"
})

...

``` 