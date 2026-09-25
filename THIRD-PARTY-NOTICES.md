# Grape IME Third-Party Notices

Grape IME is a mixed-license binary distribution. The Putao Open Binary
Distribution Terms apply only to proprietary portions for which putao520 can
grant those permissions. Third-party components retain their own licenses.

The Windows installer is built to include a release-specific `licenses`
directory containing the applicable license texts and generated Rust
dependency notices.

Principal bundled components currently include:

| Component | Source | License |
|---|---|---|
| ONNX Runtime | https://github.com/microsoft/onnxruntime | MIT |
| MiniCPM4-0.5B | https://huggingface.co/openbmb/MiniCPM4-0.5B | Apache-2.0 |
| 3D-Speaker ERes2Net | https://github.com/modelscope/3D-Speaker | Apache-2.0 |
| NVIDIA Streaming Sortformer 4spk v2.1 | https://huggingface.co/nvidia/diar_streaming_sortformer_4spk-v2.1 | NVIDIA Open Model License |
| Clay | https://github.com/nicbarker/clay | zlib/libpng |
| toml++ | https://github.com/marzer/tomlplusplus | MIT |
| Rust dependencies linked into GscImeServer.exe | crates.io/upstream repositories | Per-crate licenses; generated at release time with cargo-about |

## NVIDIA model notice

The installer includes `nvidia/diar_streaming_sortformer_4spk-v2.1`.

**Licensed by NVIDIA Corporation under the NVIDIA Open Model License**

The release build downloads and packages a copy of the applicable NVIDIA Open
Model License Agreement alongside the model notice.

## Redistribution

Redistributors must retain the license and notice materials shipped with the
installer. A third-party license may grant broader rights than the proprietary
binary-distribution terms; those third-party rights remain unaffected.
