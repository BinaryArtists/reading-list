# On software

[软件知识归类法](http://blog.csdn.net/leezy_2000/article/details/6854052)

软件的直接知识
    ①用于打造概念边界并且优化概念间逻辑关系的知识。比如，面向对象分析和设计。
    ②用于实现概念和逻辑的通用领域知识。比如编程语言。
    ③用于解决指定领域问题的专业的领域知识。比如图形算法。
软件的间接知识
    ①需求开发和描述。比如规格说明的编写。※1
    ②估算。比如功能点方法等。
    ③测试。比如验收测试等。
    ④软件工程和方法论。比如CMMI和敏捷。

## 通用的领域知识

· 编程语言（C/C++，Java，C#，Python，Perl等）
    - 元编程(Meta programming)

· 框架和类库(MFC，Boost，Struts,，Hibernate等)

· 平台(Windows API，POSIX，.Net Framework※2，Java API，C/C++ Runtime Library

· 计算机体系结构(CPU指令，虚拟存储等), 架构
    - 模型驱动架构（Model Driven Architecture)
    - 基于组件的开发（Component-Based Development）
    - 面向服务的体系结构（Service-oriented architecture）
    - Feature-oriented programming

· 实用技巧(调试方法，代码生成器等 )

## 概念与逻辑关系

1. 面向对象分析和设计／结构化分析和设计
2. 设计模式
3. 重构
4. 契约式编程
	* [契约式编程与防御式编程](http://blog.jobbole.com/107939/)
    * [怎样解释 Design by Contract (契约式设计)?](https://www.zhihu.com/question/19864652)
    * [Design by Contract (DBC) 契约式设计](http://www.jdon.com/36303)
    * [Contract-Java: Design by Contract in Java](https://www.researchgate.net/publication/246723870_Contract-Java_Design_by_Contract_in_Java)
5. UML（从形式上来看UML更近似于一种编程语言，但从其目的上来看也许归在这里是更合适的一种选择。）
6. 范型编程
7. 面向方面的编程（Aspect Oriented Programming)
8. 编程范式 (Programming paradigms)
    - [Agent-oriented](http://en.wikipedia.org/wiki/Agent-oriented_programming)
    - [Automata-based](http://en.wikipedia.org/wiki/Automata-based_programming)
    - [Component-based](http://en.wikipedia.org/wiki/Component-based_software_engineering)
    - [Flow-based](http://en.wikipedia.org/wiki/Flow-based_programming)
    - [Pipelined](http://en.wikipedia.org/wiki/Pipeline_programming)
    - [Concatenative](http://en.wikipedia.org/wiki/Concatenative_programming_language)
    - [Concurrent computing](http://en.wikipedia.org/wiki/Concurrent_computing)
    - [Relativistic programming](http://en.wikipedia.org/wiki/Relativistic_programming)
    - [Data-driven](http://en.wikipedia.org/wiki/Data-driven_programming)
    - [Declarative](http://en.wikipedia.org/wiki/Declarative_programming) (contrast: [Imperative](http://en.wikipedia.org/wiki/Imperative_programming))
    - [Constraint](http://en.wikipedia.org/wiki/Constraint_programming)
    - [Dataflow](http://en.wikipedia.org/wiki/Dataflow_programming)
    - Cell-oriented ([spreadsheets](http://en.wikipedia.org/wiki/Spreadsheet))
    - [Reactive](http://en.wikipedia.org/wiki/Reactive_programming)
    - [Intensional](http://en.wikipedia.org/wiki/Category:Intensional_programming_languages)
    - [Functional](http://en.wikipedia.org/wiki/Functional_programming)
    - [Logic](http://en.wikipedia.org/wiki/Logic_programming)
    - [Abductive logic](http://en.wikipedia.org/wiki/Abductive_logic_programming)
    - [Answer set](http://en.wikipedia.org/wiki/Answer_set_programming)
    - [Constraint logic](http://en.wikipedia.org/wiki/Constraint_logic_programming)
    - [Functional logic](http://en.wikipedia.org/wiki/Functional_logic_programming)
    - [Inductive logic](http://en.wikipedia.org/wiki/Inductive_logic_programming)
    - [End-user programming](http://en.wikipedia.org/wiki/End-user_development)
    - [Event-driven](http://en.wikipedia.org/wiki/Event-driven_programming)
    - [Service-oriented](http://en.wikipedia.org/wiki/Service-oriented_architecture)
    - [Time-driven](http://en.wikipedia.org/wiki/Time-driven_programming)
    - [Expression-oriented](http://en.wikipedia.org/wiki/Expression-oriented_programming_language)
    - [Feature-oriented](http://en.wikipedia.org/wiki/Feature_Oriented_Programming)
    - [Function-level](http://en.wikipedia.org/wiki/Function-level_programming) (contrast: [Value-level](http://en.wikipedia.org/wiki/Value-level_programming))
    - [Generic](http://en.wikipedia.org/wiki/Generic_programming)
    - [Procedural](http://en.wikipedia.org/wiki/Procedural_programming)
    - [Language-oriented](http://en.wikipedia.org/wiki/Language-oriented_programming)
    - [Discipline-specific](http://en.wikipedia.org/wiki/Service-oriented_modeling#Discipline-specific_modeling)
    - [Domain-specific](http://en.wikipedia.org/wiki/Domain-specific_language)
    - [Grammar-oriented](http://en.wikipedia.org/wiki/Grammar-oriented_programming)
    - [Dialecting](http://en.wikipedia.org/wiki/Dialecting)
    - [Intentional](http://en.wikipedia.org/wiki/Intentional_programming)
    - [Metaprogramming](http://en.wikipedia.org/wiki/Metaprogramming)
    - [Automatic](http://en.wikipedia.org/wiki/Automatic_programming)
    - [Reflective](http://en.wikipedia.org/wiki/Reflection_(computer_programming))
    - [Attribute-oriented](http://en.wikipedia.org/wiki/Attribute-oriented_programming)
    - [Template](http://en.wikipedia.org/wiki/Template_metaprogramming)
    - [Policy-based](http://en.wikipedia.org/wiki/Policy-based_design)
    - [Non-structured](http://en.wikipedia.org/wiki/Non-structured_programming) (contrast: [Structured](http://en.wikipedia.org/wiki/Structured_programming))
    - [Array](http://en.wikipedia.org/wiki/Array_programming)
    - [Nondeterministic](http://en.wikipedia.org/wiki/Nondeterministic_programming)
    - [Parallel computing](http://en.wikipedia.org/wiki/Parallel_computing)
    - [Process-oriented](http://en.wikipedia.org/wiki/Process-oriented_programming)
    - [Programming in the large and small](http://en.wikipedia.org/wiki/Programming_in_the_large_and_programming_in_the_small)
    - [Semantic](http://en.wikipedia.org/wiki/Semantic-oriented_programming)
    - [Modular](http://en.wikipedia.org/wiki/Modular_programming) (contrast: Monolithic)
    - [Object-oriented](http://en.wikipedia.org/wiki/Object-oriented_programming)
    - By [separation of concerns](http://en.wikipedia.org/wiki/Separation_of_concerns)
    - [Aspect-oriented](http://en.wikipedia.org/wiki/Aspect-oriented_programming)
    - [Role-oriented](http://en.wikipedia.org/wiki/Role-oriented_programming)
    - [Subject-oriented](http://en.wikipedia.org/wiki/Subject-oriented_programming)
    - [Class-based](http://en.wikipedia.org/wiki/Class-based_programming)
    - [Prototype-based](http://en.wikipedia.org/wiki/Prototype-based_programming)
    - [Recursive](http://en.wikipedia.org/wiki/Recursion_(computer_science))

## 专业领域知识

图形图像算法

· 网络协议

· 人工智能

· 数值/非数值类算法


## 需求开发和描述


## 估算

· 估算法。比如，COCOMO, FP等。

· 估算术。比如，使用计数等原始办法。

## 测试

· 测试驱动开发(Test Driven Development)

## 软件工程和方法论

· 轻量型方法论。比如敏捷。

· 大方法论。比如CMMI

· 综合分析。比如，《人月神话》，《人件》所做的工作。