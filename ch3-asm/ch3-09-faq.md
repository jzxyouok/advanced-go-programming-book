# 3.9. 补充说明

得益于Go语言的设计，Go汇编语言的优势也非常明显：跨操作系统、不同CPU之间的用法也非常相似、支持C语言预处理器、支持模块。同时Go汇编语言也存在很多不足：它不是一个独立的语言，底层需要依赖Go语言甚至操作系统；很多高级特性很难通过手工汇编完成。虽然Go语言官方尽量保持Go汇编语言简单，但是汇编语言是一个比较大的话题，大到足以写一本Go汇编语言的教程。本章的目的是让大家对Go汇编语言简单入门，在看到底层汇编代码的时候不会一头雾水，在某些遇到性能受限制的场合能够通过Go汇编突破限制。这只是一个开始，后续版本会继续完善。
