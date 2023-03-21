# projX-la-tcc

## 项目名称

TCC编译器LoongArch架构移植。

## 支持单位

龙芯中科技术股份有限公司

## 项目描述

Tiny C Compiler（TCC） 是用C语言实现的一个C语言编译器。它自身体积非常小，编译/链接速度非常快，可以自举（自己可以编译自己）。是“单趟编译器”（one-pass compiler）——它的预处理（tccpp.c）、词法分析（tccpp.c）、语法分析（tccgen.c）、类型检查（tccgen.c）、代码生成（<arch>-gen.c）、汇编（其实直接生成了机器码，不经过汇编）、链接，全部都是在一趟里完成的。目前支持x86、arm、arm64等。项目目标是将tcc移植到LoongArcgh平台。

## 所属赛道

2023全国大学生操作系统比赛的“OS功能挑战”赛道

## 参赛要求

* 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
* 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
* 请遵循“2023全国大学生操作系统比赛”的章程和技术方案要求

## 项目导师

* 徐成华
    - Email xuchenghua @ loongson.cn

## 难度

中-高

# License

GPL V3.0.

## 预期目标

* 实现TCC编译器的LoongArch平台支持
* 通过TCC的测试
* 鼓励完成上游提交、合并

## 参考资源

* [TCC](https://bellard.org/tcc/)
* [LoongArch docs](https://github.com/loongson/LoongArch-Documentation)。LoongArch相关文档，包括架构手册，ABI, 3A5000 CPU和7A1000桥片手册等。

## 备注

龙芯可免费提供龙芯开发资源。


