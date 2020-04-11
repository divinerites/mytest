# mytest
Repo for testing minimal hugo / bug

Original post [https://github.com/gohugoio/hugo/issues/5831](https://github.com/gohugoio/hugo/issues/5831)


- `npm install netlify-cli -g` pour installer **netlify dev**
- `netlify link` pour lier le dépôt Git et celui utilisé par Netlify
- `netlify dev` pour dev en local sur `http://localhost:8888`
- `netlify dev --live` pour dev local **partagé en live** sur `https://lagouille-abcde1234.netlify.live`
- `ps aux | grep live-tunnel` en cas de pb de tunnels
