# HumanBot Dashboard Proxy

Proyek pribadi non-komersial: dashboard web untuk HumanBot, bot Discord (Node.js) dengan profil Roblox dan pemutar musik.
Repo ini hanya meneruskan (proxy) permintaan ke server dashboard agar alamat IP dan port tidak tampil.

- Netlify: pakai file `_redirects` (status 200 = proxy).
- Vercel: pakai file `vercel.json` (rewrites). Hapus `_redirects` kalau memakai Vercel.
