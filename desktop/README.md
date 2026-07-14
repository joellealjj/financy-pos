

1. **Terminal 1 – Backend**  
   From the repo root:
   ```bash
   cd backend && npm run dev
   ```
   The backend runs on port 4000.

2. **Terminal 2 – Frontend**  
   From the repo root:
   ```bash
   cd frontend && npm run dev
   ```
   The frontend runs at http://localhost:5173.

3. **Terminal 3 – Desktop**  
   From the repo root:
   ```bash
   cd desktop && npm run dev
   ```
   Electron opens a window loading http://localhost:5173. DevTools open automatically in development mode.


You can build installable versions of the app (Linux, Windows, macOS) from the `desktop/` folder.

**Prerequisites:** Node.js, working frontend and backend builds.

**Full build** (icon + frontend + backend + installer):

```bash
cd desktop && npm run dist
```

**When the icon and frontend are already ready** (`frontend-dist/` and `resources/icon` exist), use this to build only the backend and release:

```bash
cd desktop && npm run release
```



```bash
cd desktop && npm run pack
```

