# MirrorAI 终端启动最简步骤

只保留关键运行命令。

## 手动分开 3 个终端

### 终端 1：StorySage 后端

```powershell
cd d:\Projects\mirrorai\StorySage
conda run -n storysage python src/main.py --mode server --port 8000
```

### 终端 2：MiroFish 后端

```powershell
cd d:\Projects\mirrorai\MiroFish
npm run backend
```

### 终端 3：StorySage 前端

```powershell
cd d:\Projects\mirrorai\StorySage_Frontend
npm run dev
```

## 打开网页

- 前端主页：`http://localhost:5173/`

登录后在首页点击：
- `Generate MiroFish Graph`
- `View Graph`

