# 如何在糟糕的代码上工作
[//]: # (Version:1.0.0)
工作在别人写的糟糕的代码上是常有的事。不要把他们想得太糟，直到你用他们的鞋子走路时。他们可能被要求非常自觉地快速完成一些东西来满足时间表的压力。不管之前发生了什么，为了在不清晰的代码上工作，你必须理解它。理解它需要花费一些学习时间，你必须坚持从时间表中某些部分划出一部分时间来做这件事。为了理解它们，你必须读源代码，你可能需要在上面做一些实验。

即使是为你自己，编写文档也是一个好的时机，因为尝试为你的代码编写文档会强迫你从你可能没有考虑过的角度思考，并且完成的文档可能会有用。当你在做这个时，考虑重写部分或所有代码会消耗你什么东西。是否重写一部分代码事实上真的会节省时间？你重写代码后你会更信任它吗？在这里小心你的傲慢。如果你重写它，你处理它会更容易，但下一个必须阅读它的人是否真的更加容易？如果你重写了，测试的负担在哪里？重新测试的需要是否大于可能获得的好处？

在任何对你没有编写的代码的评估中，代码的质量会影响你对风险问题的认识以及一些未知的事情。

铭记抽象和封装是很重要的，这两个程序员最好的工具，对糟糕的代码是特别好用的。你可能不能够重新设计一大块代码，但如果你可以为它增加一定量的抽象，你不用重新在这整团迷雾上工作就可以获一些好的设计所带来的好处。特别的，你可以尝试去隔离尤其糟糕的代码，这样他们就可以被独立重构。

Next [如何使用源代码控制](07-How-to-Use-Source-Code-Control.md)