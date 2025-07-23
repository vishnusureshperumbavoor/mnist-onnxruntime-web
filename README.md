```
assetsInclude: ["**/*.onnx"],
  optimizeDeps: {
    exclude: ["onnxruntime-web"],
  },
```
add the above line in defineConfig of vite.config.json

Model has to be added in public folder to load

<video src="mnist.mp4" controls width="400"></video>
