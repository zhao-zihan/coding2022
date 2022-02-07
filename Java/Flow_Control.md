# Java Study Notes

## 01.Flow Control

### 1.1 流程控制概述

![image-20220207152920063](images/image-20220207152920063.png)

### 1.2 顺序结构

![image-20220207153141270](images/image-20220207153141270.png)

### 1.3 分支结构

#### 1.3.1 if-else

![image-20220207153235029](images/image-20220207153235029.png)

![image-20220207153246290](images/image-20220207153246290.png)

```java
/*
分支结构中的if-else（条件判断结构）
一、三种结构
第一种：
if(条件表达式){
	执行表达式
}

第二种：e
if(条件表达式){
	执行表达式1
}else{
	执行表达式2
}

第三种：
if(条件表达式){
	执行表达式1
}else if{
	执行表达式2
}else if(条件表达式){
	执行表达式3
}
...
else{
	执行表达式n
}

*/
class IfTest{
	public static void main(String[] args){
		//举例1
		int heartBeats = 75;
		if(heartBeats < 60 || heartBeats > 100){
			System.out.println("需要进一步做检查");
		}
		System.out.println("检查结束");

		//举例2
		int age = 23;
		if(age < 18){
			System.out.println("你还可以看动画片");
		}else{
			System.out.println("你可以看科技电影了");
		}

		//举例3
		if(age < 0){
			System.out.println("你输入的数据不合适");
		}else if(age < 18){
			System.out.println("你还是个青少年");
		}else if(age < 35){
			System.out.println("你还是个青壮年");
		}else if(age < 60){
			System.out.println("你还是个中年");
		}else if(age < 120){
			System.out.println("你进入老年了");
		}else{
			System.out.println("你成仙了");
		}
	}
}

```

