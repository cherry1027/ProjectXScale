# ProjectScale 2040 — VS Code setup

1. Open `ProjectScale-2040.code-workspace` in Visual Studio Code.
2. If VS Code asks whether you trust the folder, choose **Yes, I trust the authors**.
3. Open **Terminal → Run Task**.
4. Run **ProjectScale: Install dependencies** if `node_modules` is not present.
5. Run **ProjectScale: Run locally**.
6. Open <http://127.0.0.1:5173/> in your browser.

The main application is in `app/page.tsx`; global styling is in `app/globals.css`.

To validate a production release, run the **ProjectScale: Production build** task.
