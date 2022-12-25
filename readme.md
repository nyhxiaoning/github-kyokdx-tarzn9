# Module Federation

## How to use

使用以下步骤运行，由于 vite 是按需编译，所以 app2 必须先打包启动，无法 2 个 App 同时是开发模式

```bash
cd app2
yarn build
yarn preview
```

new Terminal

```bash
cd app1
yarn dev
```

Both `app1` and `app2` are independently deployed apps:

- `app1`: http://localhost:3001
- `app2`: http://localhost:3002
