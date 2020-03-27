# 如何在网页中唤醒拨号键盘

| project | desc |
| ------- | ---- |
| example1 | 直接使用`<a>`的`href`属性，手动点击 |
| example2 | `<a>`订阅`onclick`事件，回调动态配置`<a>`的`href`属性，手动点击 |
| example3 | `<a>`订阅`onclick`事件，回调修改`location.href`，手动点击 |
| example4 | `<a>`订阅`onclick`事件，回调插入`<iframe>`，动态配置`<iframe>`的`src`属性，手动点击 |
| ------- | ---- |
| example5 | 直接使用`<a>`的`href`属性，自动模拟点击 |
| example6 | `<a>`订阅`onclick`事件，回调动态配置`<a>`的`href`属性，自动模拟点击 |
| example7 | `<a>`订阅`onclick`事件，回调修改`location.href`，自动模拟点击 |
| example8 | `<a>`订阅`onclick`事件，回调插入`<iframe>`，动态配置`<iframe>`的`src`属性，自动模拟点击 |
| ------- | ---- |
| example9 | 直接使用`<a>`的`href`属性，事件转发模拟点击 |
| example10 | `<a>`订阅`onclick`事件，回调动态配置`<a>`的`href`属性，事件转发模拟点击 |
| example11 | `<a>`订阅`onclick`事件，回调修改`location.href`，事件转发模拟点击 |
| example12 | `<a>`订阅`onclick`事件，回调插入`<iframe>`，动态配置`<iframe>`的`src`属性，事件转发模拟点击 |
| ------- | ---- |
| example13 | 直接使用隐藏的`<a>`的`href`属性，事件转发模拟点击 |
| example14 | 隐藏的`<a>`订阅`onclick`事件，回调动态配置`<a>`的`href`属性，事件转发模拟点击 |
| example15 | 隐藏的`<a>`订阅`onclick`事件，回调修改`location.href`，事件转发模拟点击 |
| example16 | 隐藏的`<a>`订阅`onclick`事件，回调插入`<iframe>`，动态配置`<iframe>`的`src`属性，事件转发模拟点击 |
