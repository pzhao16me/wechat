# 图灵奖第三十六届 | Ole-Johan Dahl & Kristen Nygaard:面向对象编程的鼻祖

> **一句话概括**:他们创造了Simula语言,发明了"类""对象""继承"等概念,开创了面向对象编程范式,影响了从C++到Java的所有现代编程语言。

## 🏆 获奖简介

**Ole-Johan Dahl**(1931-2002)和**Kristen Nygaard**(1926-2002)是挪威计算机科学家,面向对象编程(OOP)之父。

- **获奖年份**:2001年
- **获奖原因**:在面向对象编程方面的基本概念

## 🚀 主要贡献

### Simula语言(1965-1967)

**动机**:
模拟复杂系统(如船坞调度、交通流量)

**革命性概念**:

**类(Class)**:
```simula
class Car;
begin
    integer speed;
    procedure accelerate;
    ...
end;
```

**对象(Object)**:
```simula
ref(Car) my_car;
my_car :- new Car;
```

**继承(Inheritance)**:
```simula
class SportsCar extends Car;
begin
    procedure turboBoost;
    ...
end;
```

**虚方法(Virtual Methods)**:
运行时多态的基础

## 🌍 影响

**直接影响**:
- **Smalltalk**:Alan Kay受Simula启发
- **C++**:Stroustrup的"C with Classes"
- **Java、C#**:主流OOP语言

**思想影响**:
- **封装**:数据与方法绑定
- **抽象**:隐藏实现细节
- **多态**:同一接口,不同实现

## 🏆 获奖理由(通俗版)

他们发明的"类"和"对象"不仅是语法特性,更是思考程序结构的全新方式,改变了整个软件工程。

## 👤 个人生平

**Dahl**(1931-2002):
- 挪威奥斯陆大学数学家
- 以严谨逻辑思维著称

**Nygaard**(1926-2002):
- 运筹学背景
- 关注实际问题建模

**完美搭档**:
Nygaard提需求(模拟问题),Dahl设计语言(数学严谨)。

**历史巧合**:
两人同年(2002)相继去世,一年后(2003)被追授图灵奖,但都未能亲自领奖。

## 💭 为什么值得纪念?

OOP不只是编程技术,而是思维方式:把世界看作"对象"的集合及其交互。从游戏引擎到企业系统,OOP无处不在。

---

**总结语**: Dahl和Nygaard用Simula播下了OOP的种子,这颗种子长成了参天大树,枝叶伸向C++、Java、Python...他们证明:好的抽象比聪明的算法更持久。