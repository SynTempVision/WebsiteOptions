# CAM

| Option | Where It Runs | Difficulty | Protected Routes Supported? | DB Used? | How It Works | Pros | Cons |
|--------|---------------|------------|------------------------------|----------|--------------|------|------|
| **1. Simple HTML Status Page** | Camera | Easy | No | No | Camera serves a static HTML page | Lightweight<br>Works on all cameras | No protected routes<br>No login<br>Only basic info |
| **2. Camera BasicAuth (Built-in)** | Camera | Easy | Basic (one password) | No | Camera uses built-in BasicAuth | Quick security<br>Easy setup | Only one login<br>No roles (no operator/supervisor)<br>Ugly popup<br>Still cannot run protected routes or command logic safely |
| **3. Server-Hosted Camera UI (BEST)** | Server | Medium | Full (login, roles, sessions) | Yes | Server fetches camera data; UI protected by server | Full login system<br>Roles<br>Protected routes<br>No camera load | Requires server coding — but it’s the correct solution |
