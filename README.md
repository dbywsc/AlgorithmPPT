# AlgorithmPPT

> 基于 LaTeX Beamer 的算法教学幻灯片集  
> **作者**：dbywsc  
> **维护者**：dbywsc  
> **主页**：[GitHub - dbywsc/AlgorithmPPT](https://github.com/dbywsc/AlgorithmPPT)

---

## 摘要 (Abstract)

AlgorithmPPT 是一套使用 LaTeX Beamer 制作的、面向高校与编程竞赛选手的基础算法教学幻灯片。内容涵盖从数据结构到图算法再到动态规划、数论、复杂度分析等经典主题。每个主题以 PPT 形式呈现，配有清晰的定义、算法流程、复杂度分析、示例讲解和习题讨论。项目力求规范化排版、逻辑严谨、便于二次修改与扩展。

**关键词**：算法教学 · LaTeX Beamer · 幻灯片 · 竞赛算法 · 开源

---

## 涵盖内容

| 序号 | 主题                                 | 文件                                |
| ---- | ------------------------------------ | ----------------------------------- |
| 1    | 线性表（串、顺序表、链表）           | `线性表.tex` / `线性表.pdf`         |
| 2    | 排序（快排、归并、堆排等）           | `排序.tex` / `排序.pdf`            |
| 3    | 二分查找及其变形                     | `二分查找和二分答案.tex` / `.pdf`   |
| 4    | 前缀和、差分、离散化                 | `前缀和差分离散化.tex` / `.pdf`     |
| 5    | 双指针、单调栈、单调队列             | `双指针单调栈单调队列.tex` / `.pdf` |
| 6    | 并查集                               | `并查集.tex` / `.pdf`               |
| 7    | 深度优先搜索（DFS）                  | `深度优先搜索.tex` / `.pdf`         |
| 8    | 广度优先搜索（BFS）                  | `广度优先搜索.tex` / `.pdf`         |
| 9    | 图的存储与遍历                       | `图的存储与遍历.tex` / `.pdf`       |
| 10   | 最短路（Dijkstra、SPFA、Floyd）      | `最短路.tex` / `.pdf`               |
| 11   | 数论基础（质数、扩展欧几里得、快速幂）| `数论基础.tex` / `.pdf`             |
| 12   | 线性动态规划                         | `线性动态规划.tex` / `.pdf`         |
| 13   | 背包问题（01 背包、完全背包、分组背包）| `背包问题.tex` / `.pdf`             |
| 14   | 递归时间复杂度分析                   | `递归时间复杂度分析.tex` / `.pdf`   |

---

## 参考资料

- 《算法导论》（Introduction to Algorithms, 3rd Edition）  
- [OI-Wiki](https://oi-wiki.org/)  
- 《深入浅出程序设计竞赛》
- [Number-Theory-in-Competitive-Programming](https://github.com/GitPinkRabbit/Number-Theory-in-Competitive-Programming)
- [讲解主定理的洛谷日报](https://www.luogu.com.cn/article/awubkrso)

> **待改进**：主定理一节第一种情况公式的举例部分公式有误。

---

## 4. 使用方法

你可以直接使用 .pdf 文件，也可以自己修改 .tex 文件后手动编译。

### 4.1 环境依赖

- TeXLive 或 MiKTeX（含 `beamer`、`fontspec`、`xeCJK` 等常用宏包）  
- XeLaTeX（推荐）或 pdfLaTeX  

### 4.2 编译流程

```bash
# 以 XeLaTeX 编译为例
cd AlgorithmPPT
xelatex 线性表.tex
xelatex 排序.tex
# … 把所有 .tex 文件编译一遍，或编写 Makefile 自动化处理

