# Cup Pong Live

Two-player, real-time Cup Pong in the browser. No app, no server code.

## Deploy
1. Create a GitHub repo and upload these files (`index.html`, `netlify.toml`, `README.md`).
2. In Netlify: Add new site > Import an existing project > GitHub > pick the repo.
   Leave build command empty and publish directory as `.`, then Deploy.
   (Quicker: drag the folder onto https://app.netlify.com/drop.)

## Play
Open your site, tap **Create game**, send the link to your friend. Flick the ball up to throw.

Players connect directly (WebRTC via the free PeerJS cloud). Most networks work; a few
strict ones (some school or office Wi-Fi) may block the direct link. Switching to mobile data fixes it.
