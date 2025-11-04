# AlgorithmPPT

> 基于 LaTeX Beamer 的算法教学幻灯片集  
> **作者**：dbywsc  
> **维护者**：dbywsc  
> **主页**：[GitHub - dbywsc/AlgorithmPPT](https://github.com/dbywsc/AlgorithmPPT)

## 参考资料

- 《算法导论》（Introduction to Algorithms, 3rd Edition）  
- [OI-Wiki](https://oi-wiki.org/)  
- 《深入浅出程序设计竞赛》
- [Number-Theory-in-Competitive-Programming](https://github.com/GitPinkRabbit/Number-Theory-in-Competitive-Programming)
- [讲解主定理的洛谷日报](https://www.luogu.com.cn/article/awubkrso)

---

## 使用方法

你可以直接使用 .pdf 文件，也可以自己修改 .tex 文件后手动编译。

### 环境依赖

- TeXLive 或 MiKTeX（含 `beamer`、`fontspec`、`xeCJK` 等常用宏包）  
- XeLaTeX（推荐）或 pdfLaTeX  

### 编译流程

```bash
# 以 XeLaTeX 编译为例
cd AlgorithmPPT
xelatex 线性表.tex
xelatex 排序.tex
# … 把所有 .tex 文件编译一遍，或编写 Makefile 自动化处理

