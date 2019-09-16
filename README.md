# x-monitor-web

#### 安装
- npm 引用方式
```
npm i -S @xsyx/x-monitor-web
```
- cdn 引入(待定)

#### 基本使用
```
项目入口处
// 调用方式
try {
  new XMonitorWeb({
    key:'xxx', // 应用唯一key（必填）
    url:"xxxx", // 错误上报地址（必填）
    performanceUrl：'xxx' // 性能上报地址（必填）
  });
}catch (e) {

}

```
