<h1 align="center">Javascript Core Principles</h1>

<h2 align="center">Part 1（从零开始：JavaScript语言是如何构建起来的）</h2>

### [01 | delete 0：JavaScript中到底有什么是可以销毁的？](part1/1.delete-zero.md)

### [02 | var x = y = 100：声明语句与语法改变了JavaScript语言核心性质](part1/2.var-statement.md)

### [03 | a.x = a = {n:2}：一道被无数人无数次地解释过的经典面试题](part1/3.confused-question.md)

### [04 | export default function() {}：你无法导出一个匿名函数表达式](part1/4.export-default-function.md)

### [05 | for (let x of 1,2,3) ...：for循环并不比使用函数递归节省开销](part1/5.for-loop.md)

<h2 align="center">Part 2（从表达式到执行引擎：JavaScript是如何运行的）</h2>

### [01 | x: break x; 搞懂如何在循环外使用break，方知语句执行真解](part2/1.break.md)

### [02 | `${1}`：详解JavaScript中特殊的可执行结构](part2/2.executables.md)

### [03 | x => x：函数式语言的核心抽象：函数与表达式的同一性](part2/3.lambda.md)

### [04 | \(...x\)：不是表达式、语句、函数，但它却能执行](part2/4.not-statements.md)

### [05 | x = yield x：迭代过程的“函数式化”](part2/5.yield.md)

### [06 | throw 1;：它在“最简单语法榜”上排名第三](part2/6.throw.md)

<h2 align="center">Part 3（从原型到类：JavaScript是如何一步步走向应用编程语言的）</h2>

### [01 | 1 in 1..constructor：这行代码的结果，既可能是true，也可能是false](part3/1.constructor.md)

### [02 | new X：从构造器到类，为你揭密对象构造的全程](part3/2.new.md)

### [03 | super.x()：虽然直到ES10还是个半吊子实现，却也值得一讲](part3/3.super.md)

### [04 | return Object.create(new.target.prototype)：做框架设计的基本功](part3/4.return.md)

### [05 | 让你从一行代码看到对象的本质](part3/5.object.md)

### [06 | Object.setPrototypeOf(x, null)：连Brendan Eich都认错，但null值还活着](part3/6.property-null.md)

<h2 align="center">Part 4（从粗通到精通的进阶之路：唯一不变的是变化本身）</h2>

### [01 | a + b：动态类型是灾难之源还是最好的特性？（上）](part4/1.dynamic.md)

### [02 | a + b：动态类型是灾难之源还是最好的特性？（下）](part4/2.dynamic.md)

### [03 | (0, eval)("x = 100") ：一行让严格模式形同虚设的破坏性设计（上）](part4/3.eval.md)

### [04 | (0, eval)("x = 100") ：一行让严格模式形同虚设的破坏性设计（下）](part4/4.eval.md)

### [05 | new Function('x = 100')();：函数的类化是对动态与静态系统的再次统一](part4/5.class-function.md)

