# next-tailwind

nextjs + tailwindcss

## 使用

1. 全局安装 `@daysnap/cli` 脚手架
```bash
npm install @daysnap/cli
```

2. 在你的项目目录下执行
```bash 
dsc create my-project -t next-tailwind
```

3. 更多命令可以执行 `dsc -h` 查看
```bash
dsc -h
```


## 命令创建

```bash
npx create-next-app@latest --typescript
```


## 集成 tailwind css

- 安装依赖
```bash
npm install tailwind autoprefixer postcss
```

- 生成配置文件
```bash 
npx tailwindcss init -p
```


## 集成 prettier
```bash
npm install eslint-config-prettier prettier eslint-plugin-prettier 
```
```
// eslint config
// https://github.com/prettier/eslint-plugin-prettier#recommended-configuration
```
