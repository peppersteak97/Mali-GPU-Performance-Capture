# Use GFX-Reconstruct for Content Capture

We use [gfx-reconstruct](https://github.com/LunarG/gfxreconstruct) for capturing GPU contents ("traces") so that we will have fixed workloads each time we run.

GFX-Reconstruct ("gfxr") is a replay tool which can capture API calls on a device and later replay them on another one. This is very useful to fix workload for easy replication.

Gfxr has been added as a submodule of this repo.

## Build Gfxr

```bash
cd third_party/gfxreconstruct
```

