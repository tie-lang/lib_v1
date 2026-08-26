# tie 标准库 v1（归档）

tie 语言三层内置库的 **v1 版本归档**（library-v1，2026-08-26 归档）。
This is the archived **v1** of tie's three-tier built-in library layer.

> 后续 library-v2 重写（docs/plans/library-v2.md）将采用新语言特性（泛型 / ref 表参数 /
> struct 状态封装 / Result 错误表达）与全新接口；本仓为 v1 原始版本的一个不可变快照。
> This repo is an immutable snapshot of the v1 interfaces, superseded by the v2 rewrite
> which adopts newer language features (generics, ref table params, struct state, Result).

## 结构（Structure）

| 目录 | 层级 | 定位 |
| --- | --- | --- |
| `std/` | 标准库（34 模块） | 无状态纯函数工具（string/utf/json/sort/graph/fs/net…） |
| `rdu/` | 嵌入式基础层（7 模块） | 无栈纯标量（bits/math/ascii/crc/fixed/rnd/rdb） |
| `ext/` | 扩展库（16 文件名） | 有状态/应用级（log/test/bench/compress/ml/tui…） |

## License

本仓库使用 **TIE-LANG Open Source License v1.1**，完整文本见 [LICENSE](LICENSE)。
This repository is distributed under the **TIE-LANG Open Source License v1.1** — see [LICENSE](LICENSE) for the full text.