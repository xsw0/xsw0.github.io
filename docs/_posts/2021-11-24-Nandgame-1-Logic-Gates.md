上一篇：[Nandgame 0 介绍.md](/2021/11/24/Nandgame-0-介绍.html)

# Logic Gates

这一部分使用简单的电路实现 nand 运算，然后使用 nand 实现其他常见逻辑门电路。

## Nand

这一关是一切的开始。目标是使用最简单的开关导线搭建一个与非门。这关提供了2个原件，其中 C 接口是一个电磁铁，通电后将开关吸引到左边。解法也很简单。
> <img src="https://github.com/xsw0/xsw0.github.io/blob/gh-pages/assets/Nandgame/Logic%20Gates/Nand.png?raw=true" />

## Invert

使用 1 个与非门实现非运算
> <img src="https://github.com/xsw0/xsw0.github.io/blob/gh-pages/assets/Nandgame/Logic%20Gates/Invert.png?raw=true" />

## And

对 nand 取反得到 and
> <img src="https://github.com/xsw0/xsw0.github.io/blob/gh-pages/assets/Nandgame/Logic%20Gates/And.png?raw=true" />

## Or

使用 2 个 inv 和 1 个 nand 搭建 or
> <img src="https://github.com/xsw0/xsw0.github.io/blob/gh-pages/assets/Nandgame/Logic%20Gates/Or.png?raw=true" />

## Xor

使用 4 个 nand 搭建 xor
> <img src="https://github.com/xsw0/xsw0.github.io/blob/gh-pages/assets/Nandgame/Logic%20Gates/Xor.png?raw=true" />

---

现在，我们有简单的逻辑电路了。
