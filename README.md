# 浏览器扩展插件模板

## 项目启动

```bash
# 开发环境启动
yarn dev
```

## 生成扩展文件

```bash
# 生成扩展文件
yarn build
```

- 清单文件 `manifest.json` 位于 `/public`
- 生成的文件目录位于 `/out`

## 浏览器安装本地插件

### Edge

- 地址栏输入 `edge://extensions`
- 开启开发人员模式
- 点击 `加载解压缩的扩展`
- 选择项目生成的 `/out` 文件夹

## 相关文档

- [Chrome 扩展程序文档](https://developer.chrome.com/docs/extensions?hl=zh-cn)
- [Next.js 框架文档](https://nextjs.org/docs)
