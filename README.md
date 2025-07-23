```
assetsInclude: ["**/*.onnx"],
  optimizeDeps: {
    exclude: ["onnxruntime-web"],
  },
```
add the above line in defineConfig of vite.config.json

Model has to be added in public folder to load

[Demo Video (mnist.mp4)](mnist.mp4)
