```
assetsInclude: ["**/*.onnx"],
  optimizeDeps: {
    exclude: ["onnxruntime-web"],
  },
```
add the above line in defineConfig of vite.config.json

Model has to add in public folder to load
