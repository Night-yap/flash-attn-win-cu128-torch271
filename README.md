# flash-attn Windows Build (cu128, torch 2.7.1)

このリポジトリでは、Windows環境でビルドされた flash-attn の `.whl` ファイルを提供しています。

## ✅ 対応バージョン

- flash-attn: 2.7.4.post1
- PyTorch: 2.7.1+cu128
- Python: 3.11
- CUDA Compute Capability: 8.6 (NVIDIA RTX 3080 等)
- CXX11 ABI: False

## 📦 ファイル

`flash_attn-2.7.4.post1+cu128torch2.7.1cxx11abiFALSE-cp311-cp311-win_amd64.whl`

## 💡 使用方法

```bash
pip install flash_attn-2.7.4.post1+cu128torch2.7.1cxx11abiFALSE-cp311-cp311-win_amd64.whl
```

⚠️ 注意事項
このビルドは Windows 64bit 環境 向けです。

対応GPU: Compute Capability 8.6 以上 (RTX 30xx系など)

Python 3.11、CUDA 12.8、PyTorch 2.7.1 に対応しています。
