# Draw Call Optimization in Unity

Draw calls determine how many rendering commands Unity sends to the GPU. Reducing unnecessary draw calls improves performance, especially on mobile devices.

## Tips

- Use Static Batching
- Use Dynamic Batching
- Combine Meshes
- Use Texture Atlases
- Reduce Material Count
- Use GPU Instancing where appropriate

## Best Practices

- Keep materials shared.
- Avoid unnecessary transparency.
- Profile using the Frame Debugger.
