#### 前端组排期
https://docs.google.com/spreadsheets/d/17nYSpsiPKjYleROHYjaid6LHgcVqhWD36Fw5_ABMH-Q/edit#gid=478162514

#### 发布方案
https://confluence.bybit.com/pages/viewpage.action?pageId=1212894

#### confluence
https://confluence.bybit.com/display/FE/Frontend

const exec = require('child_process').exec

dayjs(date).isBefore(date)
dayjs(date).isAfter(date)
dayjs(date).isBetween(date,date)

Electron 1920*1080

#### node 自动部署
shelljs node-ssh

```js
var u = navigator.userAgent, app = navigator.appVersion;
  var type =  {// 移动终端浏览器版本信息
    ios: !!u.match(/\(i[^;]+;( U;)? CPU.+Mac OS X/), //ios终端
    iPad: u.indexOf('iPad') > -1, //是否iPad
    android: u.indexOf('Android') > -1 || u.indexOf('Linux') > -1, //android终端或者uc浏览器
    iPhone: u.indexOf('iPhone') > -1 || u.indexOf('Mac') > -1, //是否为iPhone或者QQHD浏览器
    trident: u.indexOf('Trident') > -1, //IE内核
    presto: u.indexOf('Presto') > -1, //opera内核
    webKit: u.indexOf('AppleWebKit') > -1, //苹果、谷歌内核
    gecko: u.indexOf('Gecko') > -1 && u.indexOf('KHTML') == -1, //火狐内核
    mobile: !!u.match(/AppleWebKit.*Mobile/i) || !!u.match(/MIDP|SymbianOS|NOKIA|SAMSUNG|LG|NEC|TCL|Alcatel|BIRD|DBTEL|Dopod|PHILIPS|HAIER|LENOVO|MOT-|Nokia|SonyEricsson|SIE-|Amoi|ZTE/), //是否为移动终端
    webApp: u.indexOf('Safari') == -1 //是否web应该程序，没有头部与底部
  };
```