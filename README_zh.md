# React + UNOCSS Taro 模板

这个项目是一个使用 Taro 框架、React 和 UNOCSS 的基础模板。Taro 是一个多端开发的解决方案，支持使用 React 来开发微信小程序、百度智能小程序、支付宝小程序、字节跳动小程序等多个平台的应用。UNOCSS 是一个开源的 Utility-First CSS 框架，使得编写样式更加高效和可维护。

## 开始

### 克隆项目

```bash
git clone https://github.com/YumeAyai/react-weapp-template
cd react-weapp-template
```

### 安装依赖

```bash
npm install
# 或者使用 yarn
yarn
```

### 运行

```bash
npm run dev:weapp
# 或者选择其他目标平台
# npm run dev:h5
# npm run dev:alipay
# npm run dev:swan
# npm run dev:tt
```

### 构建

```bash
npm run build:weapp
# 或者选择其他目标平台
# npm run build:h5
# npm run build:alipay
# npm run build:swan
# npm run build:tt
```

### 运行测试

```bash
npm test
```

## 文件结构

```plaintext
react-weapp-template/
├── config/                     # Taro 配置文件目录
├── dist/                       # 构建输出目录
├── node_modules/               # 依赖模块
├── src/                        # 项目源代码
│   ├── components/             # 组件目录
│   ├── pages/                  # 页面目录
│   ├── styles/                 # 样式目录
│   ├── app.scss                # 全局样式文件
│   └── app.ts                  # 应用入口文件
├── package.json                # 项目描述文件
├── README.md                   # 项目说明文件
└── tsconfig.json               # TypeScript 配置文件
```

## 技术栈

- [Taro](https://taro-docs.jd.com) - 多端统一开发框架
- [React](https://react.dev) - 前端组件化框架
- [UNOCSS](https://unocss.dev/) - Utility-First CSS 框架
- [TypeScript](https://www.typescriptlang.org/docs/) - JavaScript 的超集，提供了静态类型检查支持

## 贡献

欢迎贡献代码或提出建议！如果您发现任何错误或有任何改进意见，请提交 issue 或直接提出 pull request。

## 许可证

MIT
