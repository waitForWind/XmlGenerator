XmlGenerator 
============
a simple XML generator demo

用JAVA语言编写的一个简单的XML生成器，它有以下功能：
1）节点能够添加或者删除其它子节点，操作同时要保证每个节点只能有一个父节点， 一个节点只能从属于一个父节点；

2) 节点能够获取父节点对象；节点能够获取所有子节点对象。
3）节点有添加或者读取XML属性的操作；

4）当前节点有方法能打印当前节点和所有子节点（包括子孙节点）的内容；
5）可以设置XML的encoding方式。

它可以生成类似这样的XML文档：

<?xml version="1.0" encoding="UTF-8"?>
<CategoryList> 
    <Category ID="01"> 
      <MainCategory>XML</MainCategory> 
      <Description>This is a list my XML articles.</Description> 
      <Active>true</Active> 
    </Category> 
</CategoryList>
