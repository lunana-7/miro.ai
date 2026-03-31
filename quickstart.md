# MirrorAI Minimal Terminal Startup Guide

Only the essential run commands are included.

## Open 3 Separate Terminals Manually

### Terminal 1: StorySage Backend

```powershell
cd d:\Projects\mirrorai\StorySage
conda run -n storysage python src/main.py --mode server --port 8000
```

### Terminal 2: MiroFish Backend

```powershell
cd d:\Projects\mirrorai\MiroFish
npm run backend
```

### Terminal 3: StorySage Frontend

```powershell
cd d:\Projects\mirrorai\StorySage_Frontend
npm run dev
```

## Open the Web App

- Frontend home: `http://localhost:5173/`

After login, click on the home page:
- `Generate MiroFish Graph`
- `View Graph`

