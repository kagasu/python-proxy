# python-proxy
This forks allows bind to device. 

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/1202244/218603551-25e5e8a9-624f-469b-b25f-ab7367441dc1.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/1202244/218603556-43d4ea71-d224-448a-afa4-4b12940ea230.svg">
  <img src="https://user-images.githubusercontent.com/1202244/218603556-43d4ea71-d224-448a-afa4-4b12940ea230.svg">
</picture>

```
pproxy \
  -l socks5://0.0.0.0:8000/@eth0 \
  -l socks5://0.0.0.0:8001/@eth1
```

