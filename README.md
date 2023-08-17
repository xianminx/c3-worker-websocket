# Template: worker-websocket

[![Deploy to Cloudflare Workers](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/cloudflare/templates/tree/main/worker-websocket)

A simple template for working with WebSockets in Cloudflare Workers. [Check out the announcement blog post to learn more.](https://blog.cloudflare.com/introducing-websockets-in-workers/)

## Setup
(wrangler is setup as a dev deps, so no need to install a separate wrangler)
To create a `my-project` directory using this template, run:

```sh
$ npx wrangler generate my-project worker-websocket
# or
$ yarn wrangler generate my-project worker-websocket
# or
$ pnpm wrangler generate my-project worker-websocket
```


## Local Development

```sh
npm install
npm run dev
```

## Deploy

```sh
npm run deploy
```

and you will see it is deployed to : 

  https://c3-worker-websocket.xxx.workers.dev

```log
➜  c3-worker-websocket git:(main) ✗ npm run deploy

> template-worker-websocket@0.0.0 deploy
> wrangler deploy index.ts

 ⛅️ wrangler 3.5.1
------------------
Total Upload: 3.76 KiB / gzip: 1.43 KiB
Uploaded c3-worker-websocket (1.17 sec)
Published c3-worker-websocket (4.02 sec)
  https://c3-worker-websocket.xxx.workers.dev
Current Deployment ID: xxxxxxxxxx
```