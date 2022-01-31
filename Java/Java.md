# Java Study Notes

## Java Basic Syntax

### 01.Keywords and Reserved Words

#### 1.1keyword

special words with special meaning for special use in Java, all lowercased

![image-20220130221303647](images/image-20220130221303647.png)

![img](https://img-blog.csdnimg.cn/img_convert/e7b2048c652a090aaa9a77a43044863a.png)

#### 1.2 reserved words

```java
//current version of Java don't use, but reserved for future updates
goto
const
```

### 02.Identifier

#### 2.1 what is an identifier

wherever you can give it a name



#### 2.2 identifier naming rules

- composed with a-z, A-Z, 0-9, _, $
- must not begin with numbers
- must not use keywords or reserved words
- case sensitive 
- must not include a " "/space in between



#### 2.3 Java naming rules

- package: xxxyyyzzz all lowercased
- class, interface: XxxYyyZzz capitalized
- variable, method: xxxYyyZzz camel case, first word lowercased, the rest capitalized
- constant: XXX_YYY_ZZZ all caps, use _ to connect between word. eg. MAX_VALUE

```java
class IdentifierTest{
	public static void main(String[] args){
		int myNumber = 1001;
        int 学号 = 1002；
	}
}

/*
pay attention:
1. give meaningful names to improve readability
2. java uses unicode, you can write in other languages, but not recommended
*/
```



### 03.Variable

#### 3.1 declaration & use

- definition

  1. it is a storage address in the memory

  2. it's variable under the same type

  3. it's the most basic storage unit, including type, name, and value

  4.  format: type name = value

     ```java
     int example = 100;
     ```

     

- what's it for

  1. to store data in the memory

- be careful

  1. must declare first, then use
  2. function under a scope {}
  3. must not have same named variables under the same scope

- variable types (==String is a class==)

  ![Data types in Java - GeeksforGeeks](https://media.geeksforgeeks.org/wp-content/cdn-uploads/20191105111644/Data-types-in-Java.jpg)

  

  

  