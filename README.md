# intranet-redirect

GitHub Pages site for **intranet.henkelman.net**. It redirects to the Henkelman
Intranet at `https://pacgpu1.tail65fcac.ts.net/`, which is reachable on the tailnet only,
and keeps the path, so `intranet.henkelman.net/myoms` → `…/myoms`.

`404.html` is a copy of `index.html`, so every path redirects, not just `/`.

DNS (Hover): `CNAME intranet → wondermuttt.github.io`
