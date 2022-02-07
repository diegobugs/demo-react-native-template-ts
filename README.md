<h1 align="center">
  React Native Template
</h1>

📱 A template for your next React Native projects.
It is prepared with some of my basics dependencies and cool features: Typescript, react-navigation, Redux toolkit, Redux persist using MMKV.

### 💎 Features
- ✅ Last React Native version
- 🔭 Type checking [TypeScript](https://www.typescriptlang.org/)
- ⚙️ Clean project structure with Absolute Imports
- ☂️ [React Navigation](https://reactnavigation.org/)

### 🕹 How to use it

Start your project using my template by running this command:

```shell
npx react-native init SomeApp --template https://github.com/diegobugs/react-native-template.git
```

Project structure

```sh
src
├── components          # UI components with Atomic Design
│   ├── atoms
│   │   ├── Text
│   │   └── index.tsx
│   ├── molecules
│   ├── organisms
│   └── index.tsx       
├── navigator             # Navigation, main stack
│   ├── Navigator.tsx
│   └── index.ts
├── screens                # App screens
│   ├── HomeScreen
│   └── index.tsx
├── store                # Redux store
│   ├── Settings
│   ├── Store
│   │   ├── reduxStorage.tsx
│   │   ├── store.ts
│   │   └── index.ts    
│   └── index.ts    
└── utils                    # ui utils and theming
    ├── Theme
    ├── constants.tsx
    ├── index.tsx
    └── types.ts
```

### 🔖 License

This project is MIT licensed.
