# SERVER LOCAL WEBSITE

| Option | Difficulty | Coding Required? | Supports Operator + Supervisor? | DB Used? | How Protected Routes Work | Pros | Cons |
|--------|------------|------------------|----------------------------------|----------|----------------------------|------|------|
| **1. PHP Session Login** | Medium | Yes | Yes (role field) | Yes | Login sets session → role is checked at the top of protected pages | Standard method<br>Secure<br>Customizable | Requires simple PHP + DB |
| **2. .htaccess Protected Folders & Files** | Easy | No | No (no roles) | No | Folder requires username/password popup | Easiest setup<br>No coding | Popup |
