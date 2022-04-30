


```bash
subo create runnable yo --lang tinygo
wapm login ${WAPM_REGISTRY_TOKEN}
cd yo
subo build .
wapm init
wapm publish
```

URL: https://registry-cdn.wapm.io/contents/k33g/yo/1.0.0/yo.wasm