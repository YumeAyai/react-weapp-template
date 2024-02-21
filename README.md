# React + UNOCSS Taro Template

This project is a basic template using Taro framework, React, and UNOCSS. Taro is a multi-platform development solution that supports using React to develop applications for various platforms such as WeChat Mini Program, Baidu Smart Mini Program, Alipay Mini Program, and ByteDance Mini Program. UNOCSS is an open-source Utility-First CSS framework, making styling more efficient and maintainable.

## Getting Started

### Clone the Project

```bash
git clone https://github.com/YumeAyai/react-weapp-template
cd react-weapp-template
```

### Install Dependencies

```bash
npm install
# or using yarn
yarn
```

### Run

```bash
npm run dev:weapp
# or choose another target platform
# npm run dev:h5
# npm run dev:alipay
# npm run dev:swan
# npm run dev:tt
```

### Build

```bash
npm run build:weapp
# or choose another target platform
# npm run build:h5
# npm run build:alipay
# npm run build:swan
# npm run build:tt
```

### Run Tests

```bash
npm test
```

## File Structure

```plaintext
react-weapp-template/
├── config/                     # Taro configuration files
├── dist/                       # Build output directory
├── node_modules/               # Dependencies
├── src/                        # Source code
│   ├── components/             # Components
│   ├── pages/                  # Pages
│   ├── styles/                 # Styles
│   ├── app.scss                # Global styles
│   └── app.ts                  # Application entry file
├── package.json                # Project description file
├── README.md                   # Project documentation
└── tsconfig.json               # TypeScript configuration file
```

## Tech Stack

- [Taro](https://taro-docs.jd.com) - Multi-platform development framework
- [React](https://react.dev) - Frontend component framework
- [UNOCSS](https://unocss.dev/) - Utility-First CSS framework
- [TypeScript](https://www.typescriptlang.org/docs/) - Superset of JavaScript with static type checking

## Contributing

Contributions and suggestions are welcome! If you find any issues or have any improvement suggestions, please submit an issue or pull request directly.

## License

MIT
