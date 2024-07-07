# fly-uptime-kuma

Runs [uptime-kuma](https://github.com/louislam/uptime-kuma) on [fly.io](https://fly.io/).


```
fly launch \
  --copy-config \
  --auto-confirm \
  --ha=false \
  --name uptime-kuma \
  --now
```
