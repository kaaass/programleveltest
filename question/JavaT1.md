# Java习题T1

以下是一段java代码：
```Java
StringBuilder sBuilder = new StringBuilder("ja");
String java = sBuilder.append("va").toString();
System.out.println(java.intern() == java);
String drink = sBuilder.append("hothothothot").toString();
System.out.println(drink.intern() == drink);
```
资料：Java SE 7 Features and Enhancements（http://bcpu.tk/go/jdk7rel/）
通过此段代码与资料，请以jdk6、jdk7为例简单阐述jdk7更新的特性。（提示：请分别给出两版本的运行结果，指出带来此变化的更新并分析）

## 知识点

虚拟机、字符串
