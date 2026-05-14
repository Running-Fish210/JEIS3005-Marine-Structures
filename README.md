# JEIS3005 FEA and Section Property Calculation Notebooks

本仓库仅包含 Jupyter Notebook 文件，用于 JEIS3005 Marine Structures 课程中相关计算问题的求解，主要包括：

1. 二节点有限元单元的刚度矩阵计算；
2. 有限元整体刚度矩阵组装与求解；
3. 杆单元、梁单元及框架单元相关计算；
4. 截面几何参数、弹性截面模数、塑性截面模数及形状系数计算。

仓库中的 Notebook 主要分为两类：

- **函数定义文件**：用于存储有限元矩阵、坐标转换、截面参数计算等通用函数；
- **求解文件**：用于输入具体题目参数、调用函数并完成计算。

在实际使用过程中，一般只需要打开对应的求解文件并输入题目参数即可，无需手动打开或修改函数定义文件。


# JEIS3005 FEA and Section Property Calculation Notebooks

This repository contains only Jupyter Notebook files. It is used for solving calculation problems in JEIS3005 Marine Structures, mainly including two-node finite element matrix calculations and section property calculations.

The repository is organised into two types of notebooks:

- **Function definition notebooks**: used to store all reusable functions, such as finite element stiffness matrices, coordinate transformation matrices, matrix assembly procedures, and section property calculations.
- **Solution notebooks**: used to input problem-specific parameters and perform the required calculations.

During normal use, only the solution notebooks need to be opened. The function definition notebooks do not need to be opened or modified manually.
