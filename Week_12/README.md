学习笔记



## 组件化

module => (c) => component   

### 属性
attribute   属性（描述  相对于的是属性描述符）  
property    属性（继承  主要用于js继承）   
最常见的是就dom元素的 的  class herf 等等属性上面的区别：  
* 通过 getAttribute  获得是元素描述
* 通过 div.className 形式获取的书property  

-------
有几个注意点
* class  和 className
* input  的  input.value 和 getAttribute的区别
-------

| Markup set | JS set | JS change | User Inpit chang |
|:--:|:--:|:--:|:--:|:--:|
| no | ok | ok | ? |property|
| ok | ok | ok | ? |attribute|
| no | no | no | ok |state|
| no | ok | no | no |config|



