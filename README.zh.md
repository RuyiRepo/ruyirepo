[English](./README.md) | [中文](./README.zh.md)

# RuyiRepo

面向 RISC-V 的开源制品仓库，实现 RISC-V 生态软件可靠供给。

## Usage

### PyPI

地址:

```bash
https://ruyirepo.ruyicommunity.cn/pypi
```

用例:

```bash
pip install -i https://ruyirepo.ruyicommunity.cn/pypi/simple/ torch==2.10.0
```

已支持的软件:

| 软件包 | 版本 | ABI | 平台 |
|---|---|---|---|
| cffi | 2.0.0 | cp311,cp314 | manylinux_2_38_riscv64 |
| cmake | 4.2.1 | none | manylinux_2_38_riscv64 |
| coverage | 7.13.2,7.13.1,7.13.3,7.12.1b1,7.13.0,7.12.0,7.11.3,7.13.4,7.11.2,7.10.5,7.10.3,7.10.2,7.10.1,7.11.1,7.10.6,7.11.0,7.10.7,7.10.4,7.10.0,7.9.2,7.8.1,7.7.0,7.9.1,7.9.0,7.8.2,7.8.0,7.7.1,7.6.12 | cp310,cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| cryptography | 46.0.4,46.0.3,46.0.2,46.0.1 | abi3 | manylinux_2_38_riscv64 |
| cython | 3.0.6,3.1.0,3.2.4 | cp310,cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| frozenlist | 1.8.0,1.6.0,1.7.0,1.6.2,1.6.1,1.4.1,1.5.0,1.0.0 | cp310,cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| greenlet | 3.3.2,3.3.1,3.2.4,3.2.2,3.2.5,3.2.3,3.3.0 | cp310,cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| greenlet | 3.2.1,3.1.1,3.2.0,3.1.0 | cp310,cp311,cp312,cp313 | manylinux_2_38_riscv64 |
| greenlet | 3.0.1,3.0.0rc2,3.0.0rc3,3.0.0,3.0.3,3.0.0a1,3.0.0rc1 | cp310,cp311,cp312 | manylinux_2_38_riscv64 |
| greenlet | 3.0.2 | cp311,cp312 | manylinux_2_38_riscv64 |
| greenlet | 2.0.2,2.0.1,2.0.0.post0,2.0.0rc3,2.0.0a2,2.0.0rc5,2.0.0rc1,2.0.0rc4,2.0.0 | cp310,cp311 | manylinux_2_38_riscv64 |
| greenlet | 2.0.0a1 | cp310 | manylinux_2_38_riscv64 |
| libcst | 1.8.6,1.8.5,1.8.4,1.8.2,1.8.1,1.8.0 | cp310,cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| lintrunner | 0.12.11 | none | manylinux_2_38_riscv64 |
| llvmlite | 0+untagged.g2a780ed,0+untagged.g2675627,0.0.0,0.47.0 | cp310,cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| llvmlite | 0.46.0 | cp314 | manylinux_2_38_riscv64 |
| lxml | 6.0.0a0,7.0.0a0,6.0.0,5.3.0,6.0.3,5.4.0 | cp311 | manylinux_2_38_riscv64 |
| markupsafe | 3.0.3,3.0.2,3.0.1,3.0.0,2.1.5,2.1.4,2.1.3,2.1.2,2.1.1,2.1.0 | cp310,cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| markupsafe | 0.21,0.20,0.19 | cp310,cp311 | manylinux_2_38_riscv64 |
| ml_dtypes | 0.5.4 | cp310,cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| msgpack | 1.0.6,1.0.6rc1,1.0.8 | cp310,cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| msgpack | 1.0.4rc1,1.0.5,1.0.4,1.0.5rc1 | cp310,cp311,cp312 | manylinux_2_38_riscv64 |
| msgpack | 1.0.3rc1,1.0.3 | cp310 | manylinux_2_38_riscv64 |
| multidict | 6.7.1,6.6.2,6.6.1,6.5.1,6.5.0,6.6.4,6.6.0,6.7.0,6.4.4,6.4.3,6.4.2,6.4.1,6.4.0,6.3.0,6.2.0,6.3.2,6.3.1,6.0.5,5.2.0a25,5.2.0a0,6.0.3,6.0.4,6.0.2,5.2.0a15,5.2.0a12,5.2.0a24,6.0.1,6.0.0 | cp310,cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| ninja | 0.1.dev20+gb4afc8eee,1.13.0 | none | manylinux_2_38_riscv64 |
| numba | 0.64.0+3.g52f1433,0+untagged.151.g2403925,0+untagged.136.g360a5cf,0.64.0,0+untagged.93.g77e1af6 | cp314 | manylinux_2_38_riscv64 |
| numpy | 2.4.2,2.4.4,2.4.3,2.3.5,2.3.4,2.3.3,2.4.1,2.4.0rc1,2.4.0,2.3.1,2.3.2 | cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| numpy | 2.0.0rc1,2.2.5,2.2.2,2.2.3,2.2.1,2.2.6,2.2.4 | cp310,cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| onnx | 1.20.0 | abi3,cp310,cp311 | manylinux_2_38_riscv64 |
| onnx | 1.20.1 | abi3,cp311 | manylinux_2_38_riscv64 |
| optree | 0.18.0 | cp311,cp314 | manylinux_2_38_riscv64 |
| pandas | 0+untagged.20.g2d43452 | cp311,cp314 | manylinux_2_38_riscv64 |
| pandas | 0+untagged.20.g6aaab49,0+untagged.20.g1461fba,0+untagged.20.g8a99331,0+untagged.20.g363375b,0+untagged.20.g7bd0a5f,3.0.0rc2,3.0.0,3.0.2,3.0.0rc1,3.0.1,2.2.3+1.geed2146 | cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| pandas | 2.2.2+1.g349e364 | cp311,cp312 | manylinux_2_38_riscv64 |
| pillow | 11.0.0 | cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| propcache | 0.4.1,0.3.2,0.2.1,0.1.0,0.3.0,0.4.0,0.3.1,0.2.0,0.0.0.dev0,0.0.0 | cp310,cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| psutil | 7.2.2,6.1.1,7.2.1,7.2.0,7.1.2,7.1.3,7.1.1,7.0.0,7.1.0,6.1.0,5.9.7,5.9.6,6.0.0 | abi3 | manylinux_2_38_riscv64 |
| psutil | 5.9.3,5.9.2,5.9.0,5.9.1,5.7.3,5.7.1,5.6.5,5.6.4,5.6.3,5.8.0,5.7.2,5.6.7,5.7.0,5.6.6 | cp310,cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| pynacl | 1.6.2,1.6.1,1.6.0,1.4.0 | cp310,cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| pynacl | 1.5.0 | cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| pywavelets | 1.7.0 | cp311,cp314 | manylinux_2_38_riscv64 |
| scikit_image | 0.22.0 | cp310,cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| sentencepiece | 0.1.97,0.1.96,0.1.94,0.1.95 | cp310,cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| sqlalchemy | 2.1.0b2,2.1.0b1,2.0.48,2.0.41,2.0.47,2.0.46,2.0.45,2.0.44,2.0.43,2.0.42,2.0.39,2.0.38 | cp310,cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| sqlalchemy | 2.0.23 | cp310,cp313,cp314 | manylinux_2_38_riscv64 |
| sqlalchemy | 2.0.24 | cp313,cp314 | manylinux_2_38_riscv64 |
| thriftpy2 | 0.5.3 | cp311,cp314 | manylinux_2_38_riscv64 |
| tlparse | 0.4.0 | none | manylinux_2_38_riscv64 |
| torch | 2.9.0 | cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| torch | 2.10.0 | cp310,cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| torch | 2.8.0,2.7.0 | cp310,cp311,cp312,cp313 | manylinux_2_38_riscv64 |
| websockets | 15.0.1,14.2,14.0,14.1,12.0,11.0.1,10.3,5.0.1,9.0,9.0.1,8.1,8.0.2,8.0 | cp310,cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| websockets | 9.0.2 | cp310,cp313,cp314 | manylinux_2_38_riscv64 |
| wrapt | 2.1.1,2.2.0rc6,2.2.0rc9,2.2.0rc7,2.0.0rc6,1.17.2,2.2.0rc1,2.2.0rc2,2.2.0rc10,2.0.1rc1,2.2.0rc3,2.1.0.dev1,2.0.1,2.0.0rc1,2.0.0rc3,2.2.0rc5,2.2.0rc4,2.0.0,2.0.0rc4,2.1.2,2.1.0.dev2,1.17.1,2.1.0,2.1.2rc1,2.1.0rc1,2.0.0rc5,2.0.0rc2,1.17.3,1.17.0.dev3 | cp310,cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| yarl | 1.23.0,1.21.0,1.19.0,1.18.3,1.18.1,1.18.0,1.16.0rc0,1.15.5,1.15.4,1.15.3,1.15.1,1.17.2,1.14.0,1.13.0,1.12.0,1.11.0,1.10.0,1.15.0,1.12.1 | cp310,cp311,cp312,cp313,cp314 | manylinux_2_38_riscv64 |
| yarl | 1.22.0 | cp311,cp314 | manylinux_2_38_riscv64 |


## Feedback

若使用中遇到问题，欢迎提交 [Issue](https://github.com/RuyiRepo/issues)。

