# ⚛️ Physics 3D Lab — University Physics Laboratory

An interactive 3D physics laboratory application featuring university-grade physical simulations, soft anti-glare studio lighting, and real-time physical telemetry.

## 🚀 Deploy to Render in 2 Steps

### Option A: Direct Blueprint Deployment (Recommended)
1. Push this repository to **GitHub** or **GitLab**.
2. Go to your [Render Dashboard](https://dashboard.render.com/).
3. Click **New +** > **Blueprint**.
4. Select your repository. Render will automatically detect `render.yaml` and deploy it instantly as a high-performance **Static Site** on Render's global CDN for free!

### Option B: Manual Static Site Creation
1. Go to [Render Dashboard](https://dashboard.render.com/) > **New +** > **Static Site**.
2. Connect your Git repository.
3. Configure:
   - **Name**: `physics-3d-lab`
   - **Branch**: `main`
   - **Build Command**: *(leave empty)*
   - **Publish Directory**: `./`
4. Click **Create Static Site**.

### Option C: Web Service (Node.js)
If you prefer running it as a Node service:
- **Build Command**: *(leave empty)*
- **Start Command**: `node server.js`
