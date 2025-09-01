One-Click Deploy (preconfigured for this repo)
----------------------------------------------

### Deploy Frontend (Vercel)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/its-phillip/edutech-hub-hackathon-3&project-name=edutech-hub&repository-name=edutech-hub-hackathon-3&root-directory=frontend&build-command=npm%20run%20build&output-directory=dist)

### Deploy Frontend (Netlify)
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/its-phillip/edutech-hub-hackathon-3)

### Deploy Backend (Render)
[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)

Notes:
- After deploying the backend, set the backend URL as `VITE_API_URL` in your frontend environment variables on Vercel/Netlify.
- For Render, set the root directory to `backend` and start command `node index.js`.
- If you want Railway instead of Render, tell me and I'll add a Railway button.
