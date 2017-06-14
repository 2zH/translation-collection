## 关于本书

这是一本关于函数式的书。我们将会使用全世界最受欢迎的函数式编程语言: Javascript。有些人可能会认为选择JavaScript来学习函数式并不明智，因为函数式编程风格并非当下JavaScript编程主流风格，目前的主流观点认为JavaScript是一门命令式编程语言。但是我相信这是学习函数式编程最好的方法，以下是几点理由：

* **你很容易在每天的日常工作中使用它.**

  通过每天的实际项目实践和应用已学到的函数式知识成为可能，而不是在夜晚或周末，使用深奥的函数式语言练习编写一些玩具项目。
  
* **我们在开始进行函数式编程前不需要先学习所有相关的知识.**

  在一门纯函数式的语言中，你不通过monads去打印一个变量或者读取一个DOM节点是不被允许的。但在JavaScript中，我们能稍微作作弊以此直接去学习函数式的精华。这使得我们更容易入门函数式编程，因为它是一门混式编程语言，当你感到不解时，可以回归你熟悉的编写方式中。

* **该语言足以编写良好的函数式代码.**

  我们仅需要一两个轻量的库就可以模仿例如Scala或Haskell的所有特性。目前面向对象编程(Object-oriented programing)在业界仍处于主导地位，但很明显这在JavaScript使用起来十分别扭，用起来像是在高速公路上露营或是穿着水鞋跳踏踏舞。我们不得不到处使用```bind```来防止```this```的指向发生改变，我们没有```classes```(目前还没有)，我们有各种各样的hack来应付忘记加```new```关键字出现的诡异行为，私有成员只能通过闭包(closure)来使用。对更多人来说，函数式编程在各方面更加自然。

也就是说，毫无疑问的是通过这本书你将了解到强类型函数式语言最好的编写样例。JavaScript是我们学习这种范式的一种手段，将它应用于什么地方则完全取决于你自己。幸运的是，函数式的接口方案仅仅只是一种数学运算，能够在任何编程语言中使用。你可以在swiftz, scalaz, haskell, purescript,或其它偏数学的编程语言环境中找到它。

### Gitbook(更好的阅读体验)
- [Read it online](https://drboolean.gitbooks.io/mostly-adequate-guide/content/)
- [Download EPUB](https://www.gitbook.com/download/epub/book/drboolean/mostly-adequate-guide)
- [Download Mobi(Kindle)](https://www.gitbook.com/download/mobi/book/drboolean/mostly-adequate-guide)

### Do it yourself

```
git clone https://github.com/DrBoolean/mostly-adequate-guide.git

cd mostly-adequate-guide/
npm install gitbook-cli -g
gitbook init

brew update
brew install Caskroom/cask/calibre

gitbook mobi . ./functional.mobi
```
# 目录

见 [SUMMARY.md](https://github.com/MostlyAdequate/mostly-adequate-guide/blob/master/SUMMARY.md)

## Contributing

见 [CONTRIBUTING.md](https://github.com/MostlyAdequate/mostly-adequate-guide/blob/master/CONTRIBUTING.md)

### 翻译

见 [TRANSLATIONS.md](https://github.com/MostlyAdequate/mostly-adequate-guide/blob/master/TRANSLATIONS.md)

### FAQ

见 [FAQ.md](https://github.com/MostlyAdequate/mostly-adequate-guide/blob/master/FAQ.md)