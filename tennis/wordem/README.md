# word embedding

needs to be on webserver as chrome doesn't allow local js communication:

```
Access to script at 'file:///home/hayden/Downloads/test/three.module.js' from origin 'null' has been blocked by CORS policy: Cross origin requests are only supported for protocol schemes: http, data, chrome, chrome-extension, https.
```

the js need to be modules: `<script type="module" src="./name.js"></script>`