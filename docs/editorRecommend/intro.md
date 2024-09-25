
## 编辑器/ide介绍⌨️
---

&emsp;&emsp;在挑选编辑器之前，我们首先要考虑它的功能有哪些：

- 自动补全和提示
- 类型检测
- 自动格式化
- ... ...


### 那么这里有一个问题，编辑器是如何拥有这些功能的?

这里简单介绍一下四个功能部件:

#### 1. [LSP](https://blog.csdn.net/u012930117/article/details/79291677#:~:text=Language%20S)

> ~~(Lao ** ** )~~ ( **Language Server Protocol**)

- 代码补全（根据上下文提供代码补全的建议）
- 检测代码中的错误和警告
- 跳转到定义
- 支持重构操作

---

#### 2. [DAP](https://www.jianshu.com/p/da7336676cda)

> (**Debug Adapter Protocol**),DAP 是一种协议，用于在编辑器和调试器之间进行通信。

&emsp;&emsp;例如和debug有关的：断点管理、调试时的变量查看、调用堆栈、控制执行

---

#### 3. [Linter](https://www.zhihu.com/question/28421865) 

- 检测语法错误
- 确保代码符合特定的编码规范
- 检测可能导致错误的代码模式
- 提供改进代码质量的建议，简单的优化

---

#### 4. Formatter

>  &emsp;&emsp;不同语言的编写时的语法不同,它们编写时遵循的格式也不同

&emsp;&emsp;formatter就是用来格式化代码的，在一些ide中在保存时或者按快捷键触发的代码格式调整的行为，例如缩进、换行、代码对齐等的调整