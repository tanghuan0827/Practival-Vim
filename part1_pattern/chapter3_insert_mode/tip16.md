# 技巧16: 随时随地做运算
> 使用表达式寄存器做运算

1. 大部分Vim`寄存器`保存的都是**文本/字符串**
2. `表达式寄存器`可以执行一个vim脚本,并返回结果
> `=`指明使用表达式寄存器, 插入模式中`<C-r>=`表明使用表达式寄存器


### 例子: 插入模式中计算6*35

![tip16](../../images/tip16.png)  


<br>  

|上一篇|下一篇|
|:---|---:|
|[技巧15 不离开插入模式, 粘贴寄存器中的文本](tip15.md)|[技巧17 用字符编码插入非常用字符](tip17.md)|
