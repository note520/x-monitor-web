# x-monitor-web

#### 安装
- npm 引用方式
```
npm i -S @xsyx/x-monitor-web
```
- cdn 引入
```
<script type="text/javascript" src="//xsyx-front-asset.oss-cn-shenzhen.aliyuncs.com/common-lib/default/x-monitor-web/v0.1.0/x-monitor-web.js"></script>
```
#### 基本使用
```
项目入口处(最好是在项目引入后的第一行)
// 调用方式
try {
  new XMonitorWeb({
    key:'xxx', // 应用唯一key（必填）
    url:"xxxx", // 错误上报地址（必填）
    performanceUrl：'xxx' // 性能上报地址（选填）
  });
}catch (e) {

}

```
