---
layout: home
title: HHVM
id: home
---

## HHVM 是什么？

HHVM 是一款 [开源](http://github.com/facebook/hhvm) 的虚拟机，用于执行 [Hack](http://hacklang-cn.org/) 语言编写的程序。 HHVM 使用即时编译 (JIT) 方法来实现出色的运行时性能，同时保持不可思议的开发灵活性。

HHVM 支持 [Hack](http://hacklang-cn.org/) 编程语言。我们将会频繁迭代，并且会经常发布新版本。如果你发现类型检查器或运行时出现了 bug，请 [提交 issue](https://github.com/facebook/hhvm/issues/new) 告诉我们。

<div class="gridBlock">
  <div class="blockElement twoByGridBlock alignLeft">
    <div class="blockContent">
      <h3>HHVM 特性</h3>
      <ul>
        <li><a href="http://hacklang-cn.org/">Hack 编程语言</a></li>
        <li><a href="http://www.hhvm-cn.com/blog/2027/faster-and-cheaper-the-evolution-of-the-hhvm-jit">即时编译</a></li>
        <li><a href="https://github.com/facebook/hhvm/wiki/Extension-API">HHVM 本地接口 (HNI)</a></li>
        <li>内置支持 <a href="http://docs.hhvm-cn.com/hhvm/basic-usage/proxygen">Proxygen</a> 和 <a href="http://docs.hhvm-cn.com/hhvm/advanced-usage/fastCGI">FastCGI</a></li>
        <li><code>HPHPd</code> 调试器</li>
        <li><a href="http://docs.hhvm-cn.com/hhvm/">更多</a> ...</li>
      </ul>
    </div>
  </div>

  <div class="blockElement twoByGridBlock alignLeft">
    <div class="blockContent">
      <h3>JIT 编译器</h3>
      <p>
        HHVM 并不是<a href="https://zh.wikipedia.org/zh-cn/HipHop_for_PHP#%E6%AD%B7%E5%8F%B2">将源代码直接通过解释或编译转换成 C++ 的代码</a>，而是将 Hack 语言的代码编译为中间字节码。然后，中间字节码在运行时由即时编译器 (<a href="https://zh.wikipedia.org/zh-cn/%E5%8D%B3%E6%97%B6%E7%BC%96%E8%AF%91">JIT</a>) 动态优化后翻译成 <a href="https://zh.wikipedia.org/zh-cn/X86-64">x64</a> 机器码。在这个编译过程中，会进行各种无法在静态编译的二进制文件中进行的优化，从而使你的 Hack 程序具有更高的性能。
      </p>
    </div>
  </div>
</div>
