> 📚 原书地址：[https://en.algorithmica.org/hpc/](https://en.algorithmica.org/hpc/)

本项目致力于翻译 Sergey Slotin 所著的《Algorithms for Modern Hardware》，该书深入探讨了在现代硬件架构上优化算法性能的策略，涵盖了从 CPU 缓存机制、SIMD 指令集到外部内存模型等多个方面。

---



## 📖 项目简介

《Algorithms for Modern Hardware》是一本面向性能工程师、算法研究者以及希望提升代码性能的开发者的开源教材。作者通过大量实证案例，展示了如何利用现代硬件特性优化算法实现，包括但不限于：

- 多种二分查找优化版本，实现了对 `std::lower_bound` 的显著加速；
- 利用 SIMD 实现的高效 `argmin` 操作；
- 提升约 50 倍性能的 Floyd-Warshall 算法实现；
- 高性能的 GCD、整数因数分解、矩阵乘法等算法；
- 针对分支预测、内存访问模式的基准测试。

---



## 📂 项目结构

- `chapters/`：按章节组织的翻译内容；
- `images/`：书中插图和示意图；
- `scripts/`：辅助脚本（如构建、校对等）；
- `README.md`：项目说明文档（即本文件）；
- `LICENSE`：版权和许可信息。

---



## 🚧 翻译进度

| 章节编号 | 章节标题               | 翻译状态 | 校对状态 |
|----------|------------------------|----------|----------|
| 1        | Complexity Models     | ⏳ 进行中 | ❌ 未开始 |
| ...      | ...                    | ...      | ...      |

> 📌 注：欢迎通过 Pull Request 参与翻译和校对工作！

---



## 🤝 参与贡献

我们欢迎任何形式的贡献，包括但不限于：

- 翻译章节内容；
- 校对已翻译内容；
- 提出改进建议或发现错误；
- 提供术语统一建议。

---



## 📄 版权声明

原书作者：Sergey Slotin  
原书链接：[https://en.algorithmica.org/hpc/](https://en.algorithmica.org/hpc/)  
原书代码仓库：[https://github.com/sslotin/amh-code](https://github.com/sslotin/amh-code)

本翻译项目遵循原作者的开源许可协议，**仅用于学习和研究目的!** 如需转载或引用，请注明出处。

---



## 📬 联系方式

如有任何疑问或建议，欢迎通过以下方式联系我们：

- 提交 Issue；
- 发送 Pull Request；
- 邮件联系：[fan.jiaming@hotmail.com](mailto:fan.jiaming@hotmail.com)

---

感谢您的关注与支持！🙏
