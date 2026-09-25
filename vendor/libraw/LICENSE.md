# 第三方组件：LibRaw-Wasm

本目录中的 `index.js`、`worker.js`、`libraw.js`、`libraw.wasm` 来自 npm 包 [libraw-wasm](https://www.npmjs.com/package/libraw-wasm) 1.6.0（[ybouane/LibRaw-Wasm](https://github.com/ybouane/LibRaw-Wasm)），只删去了 source map 注释，没有做其它修改。

| 组件 | 许可证 |
|---|---|
| LibRaw-Wasm 封装代码 | ISC |
| [LibRaw](https://www.libraw.org/) | LGPL 2.1 或 CDDL 1.0，任选其一 |
| [Little CMS](https://www.littlecms.com/) | MIT |

编译好的 WebAssembly 中包含 LibRaw 与 Little CMS。LibRaw 的源代码见 https://github.com/LibRaw/LibRaw ；替换本目录中的 `libraw.wasm` 即可换用其它版本的 LibRaw。
