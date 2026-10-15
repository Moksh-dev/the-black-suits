# THE BLACK SUITS

A responsive React and TypeScript demo for an Indian legal information platform. The interface uses fictional sample content and local demo state; it is not legal advice, secure storage, or a live service.

## Prerequisites

- Windows 10 or 11
- Node.js 20.19+ or 22.12+ and npm

## Install and run (PowerShell)

```powershell
cd "C:\Users\goelm\OneDrive\Desktop\PITCHERS SHOWDOWN"
npm install
npm run dev
```

Open the URL printed by Vite in the terminal (usually `http://localhost:5173`). The app makes no backend requests. `VITE_API_BASE_URL` is reserved for a future backend adapter and is not used by this demo.

## Build and checks

```powershell
npm run typecheck
npm run build
npm run preview
```

There is no test runner configured yet. Demo matters are stored in this browser's local storage; document selections and chat messages are temporary page state. Clear demo matters on Settings or remove this site's local storage in the browser.

## Troubleshooting

- If `npm install` fails, confirm Node.js/npm are installed and that the package registry is reachable, then retry.
- If the dev port is in use, Vite prints another available local URL.
- Refreshing clears temporary chat, checklist and document selections. Matters persist in local storage until cleared.
- No account, secure file vault, AI model, lawyer directory or legal submission service is connected.
