# wython

## 安装与运行

使用pip安装wython。  
`pip install wython`  
运行wython。  
`python -m wython test.docx`  
请将python代码放入test.docx文件中。

## 什么是wython？

$$Java + python = jython$$  
$$word + python = wython$$  

~~显然如果我将其命名为python_word等，这看起来像python中解析word的库。~~  
word可以看成加强版的文本文件，因为其中可以包含图片等元素。wython希望充分利用这些特点，使代码中元素多元化。  
例如，直接在代码中  
`test = ~ # 其中~处在word中放入一个图片`  
这相当于直接为变量test赋值，类型为图片。此过程就像代码  
```python
t_list = [1, 2, 3]
t_string = "今天是2024年12月28日"
```
进行赋值操作一样，只不过不需要[ ]、" "表示引用。word文件中的图片，相当于上述例子中文本表示的列表和字符串的值。
