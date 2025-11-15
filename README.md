# SmartOps

基于 Electron 的桌面应用，支持多标签页和工具栏视图管理。

## 技术栈

- **Electron** 38 - 跨平台桌面应用框架
- **React** 19 - UI 框架
- **TypeScript** 5 - 类型安全
- **Vite** 7 - 构建工具
- **Electron Vite** 4 - Electron 专用构建配置
- **TanStack Router** - 文件路由
- **Tailwind CSS** 4 - 样式框架
- **Zustand** - 状态管理
- **Lucide React** - 图标库
- **Electron Builder** - 应用打包

## 开发

```bash
# 安装依赖
pnpm install

# 启动开发环境
pnpm dev

# 类型检查
pnpm typecheck

# 代码格式化
pnpm format
```

## 构建

```bash
# 构建所有平台
pnpm build

# 构建 macOS
pnpm build:mac

# 构建 Windows
pnpm build:win

# 构建 Linux
pnpm build:linux
```

