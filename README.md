# DeepSpeed Windows Wheels Collection
Pre-compiled DeepSpeed wheels for Windows - **no build tools required**! 🚀

Building DeepSpeed from source on Windows is notoriously difficult. These wheels are ready to use.

## 🎯 Available Wheels

### DeepSpeed
Distributed training library with ZeRO memory optimization and high-performance kernels.

| Version | Python | PyTorch | CUDA | Download |
|---------|--------|---------|------|----------|
| 0.18.2 | 3.10 | 2.5+ | 12.x| [Release](../../releases) |
| 0.17.6 | 3.12 | 2.3+ | 12.x | [Release](../../releases) |
| 0.17.6 | 3.11 | 2.3+ | 12.x | [Release](../../releases) |
| 0.17.6 | 3.10 | 2.3+ | 12.x | [Release](../../releases) |

**Note:** DeepSpeed is flexible with PyTorch versions. The listed version is the minimum tested.

### More packages coming soon...
Got a specific wheel request? Open an issue!


## 🔧 Known Limitations

Some DeepSpeed features are disabled on Windows:
- Async I/O operations (Linux-only)
- GPUDirect Storage (Linux-only)
- Some inference ops

Core training features (ZeRO, mixed precision, gradient accumulation) work perfectly!

## 🤝 Contributing

Found these wheels helpful? Star the repo! ⭐

Need a different configuration? Open an issue!

## 📜 License

DeepSpeed is licensed under Apache 2.0. These are pre-compiled distributions.

---

