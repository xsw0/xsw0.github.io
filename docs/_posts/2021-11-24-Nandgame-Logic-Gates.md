# Logic Gates

这一部分使用简单的电路实现 nand 运算，然后使用 nand 实现其他常见逻辑门电路。

## Nand

这一关是一切的开始。目标是使用最简单的开关导线搭建一个与非门。这关提供了2个原件，其中 C 接口是一个电磁铁，通电后将开关吸引到左边。解法也很简单。
> ![Nand](https://github.com/xsw0/xsw0.github.io/tree/gh-pages/docs/Nandgame/Logic%20Gates/Nand.png "Nand")

## Invert

使用 1 个与非门实现非运算
> ![Invert](https://github.com/xsw0/xsw0.github.io/tree/gh-pages/docs/Nandgame/Logic%20Gates/Invert.png "Invert")

## And

对 nand 取反得到 and
> ![And](https://github.com/xsw0/xsw0.github.io/tree/gh-pages/docs/Nandgame/Logic%20Gates/And.png "And")

## Or

使用 2 个 inv 和 1 个 nand 搭建 or
> ![Or](https://github.com/xsw0/xsw0.github.io/tree/gh-pages/docs/Nandgame/Logic%20Gates/Or.png "Or")

## Xor

使用 4 个 nand 搭建 xor
> ![Xor](https://github.com/xsw0/xsw0.github.io/tree/gh-pages/docs/Nandgame/Logic%20Gates/Xor.png "Xor")

---

现在，我们有简单的逻辑电路了。