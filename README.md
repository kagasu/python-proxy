# python-proxy
This fork allows bind to network device. 

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/1202244/218605530-82e96479-01a3-4371-89a7-656b874a508e.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/1202244/218605535-7759398c-ccd5-4b61-8a7e-46d128ced1dd.svg">
  <img src="https://user-images.githubusercontent.com/1202244/218605535-7759398c-ccd5-4b61-8a7e-46d128ced1dd.svg">
</picture>

```
pproxy \
  -l socks5://0.0.0.0:8000/@eth0 \
  -l socks5://0.0.0.0:8001/@eth1
```

# Install
```
git clone https://github.com/kagasu/python-proxy
pip install -e python-proxy
```
