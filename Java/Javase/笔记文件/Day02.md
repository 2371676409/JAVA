# 1. 基础语法

## 1. 计算机存储单元

* 1. 什么是字节：计算机最小的存储单元（水杯）----bit（位，比特位）

* 2. 其他的存储单位：
  * 1B（字节）= 8 bit
  * 1KB             = 1024（B）
  * 1MB            = 1024KB
  * 1GB             =  1024MB

## 2. 进制

* 1. 十进制：10 12 15

* 2. 二进制：1010 1000 ，0010 0010

* 3.需求 ： 10转换成二进制
  ![](assets/Day02/image-20230310192001214.png)
# 2. 数据类型

## 1. 基本数据类型

**演示基本类型的Demo**
### 1.byte
存储范围 =  [ -128 - 127 ]
存储字节 = 1字节  =  8位
```java
public class ByteDemo{
	public static void main(String[] args){
		byte b = 12;
		System.out.println(b);
	}
}

//如果我们 存200
```

### 2.Short
存储范围 =  [ -32768 - 32767 ]
存储字节 = 2字节  =  16位
```java
public class ShortDemo{
	public static void main(String[] args){
	Short sh = 12;
		System.out.println(sh);
	}
}
```

### 3.Int
存储范围 =  [ -2147483648 - 2147483648 ]
存储字节 = 4字节  =  32位
```java
public class IntDemo{
	public static void main(String[] args){
	Int in = 12;
		System.out.println(in);
	}
}
```

### 3.Long
存储范围 =  [ -2^63 - 2^63-1 ]
存储字节 = 8字节  =  64位
```java
public class LongDemo{
	public static void main(String[] args){
	Long lo = 12;
		System.out.println(lo);
	}
}

