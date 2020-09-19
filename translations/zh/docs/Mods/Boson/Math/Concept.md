# 概念

ZenScript 中的数学大部分使用可以通过四个基本操作来覆盖：添加、减去、 乘数和除法。 ZenScript 还提供对 `pow` 函数的访问，这些函数执行电源操作。 但情况确实如此。 无法进行更先进的数学操作， 并且需要完全重新实现使用 查找表，不会从硬件在这方面的优化中受益，特别是现代CPU。

这里是 ZenScriptX 数学，提供了一组类和一些基本的算术操作，可能是 的普遍有用性， 同时也从硬件优化中受益， 因为其中大多数是在本地一级执行的 (通过VM ZenScript 运行的几个间接) 。

每个文档部分将为用户提供一个提供的函数和行为列表。

当前提供的已执行的类包括：

- [数学函数](/Mods/Boson/Math/Math/) 用于常见的数学函数(例如sin、cos、对数...)