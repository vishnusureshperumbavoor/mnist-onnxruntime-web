```
assetsInclude: ["**/*.onnx"],
  optimizeDeps: {
    exclude: ["onnxruntime-web"],
  },
```
add the above line in defineConfig of vite.config.json

Model has to be added in public folder to load

[Twitter/X Demo](https://x.com/vspeeeeee/status/1948057594507223303)
