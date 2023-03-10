# 1. 基础语法

## 1. 计算机存储单元

* 1.什么是字节：计算机最小的存储单元（水杯）----bit（位，比特位）

* 2.其他的存储单位：
```java
   1B（字节）= 8 bit
   1KB       = 1024（B）
   1MB       = 1024KB
   1GB       =  1024MB
```

## 2. 进制

* 1.十进制：10 12 15

* 2.二进制：1010 1000 ，0010 0010

* 3.需求 ： 10转换成二进制

  ![](assets/Day02/image-20230310192001214.png)
# 2. 数据类型

## 1. 基本数据类型

### 1.整形

**演示整形的Demo**

#### 1.byte
存储范围 =  [ -128 - 127 ]
存储字节 = 1 字节  =  8 位
```java
public class ByteDemo{
	public static void main(String[] args){
		byte b = 12;
		System.out.println(b);
	}
}

//如果我们 存200
```

#### 2.Short
存储范围 =  [ -32768 - 32767 ]
存储字节 = 2 字节  =  16 位
```java
public class ShortDemo{
	public static void main(String[] args){
	Short sh = 12;
		System.out.println(sh);
	}
}
```

#### 3.Int
存储范围 =  [ -2147483648 - 2147483648 ]
存储字节 = 4 字节  =  32 位
```java
public class IntDemo{
	public static void main(String[] args){
	Int in = 12;
		System.out.println(in);
	}
}
```

#### 3.Long
存储范围 =  [ -2^63 - 2^63-1 ]
存储字节 = 8 字节  =  64 位
```java
public class LongDemo{
	public static void main(String[] args){
	Long lo = 12;
		System.out.println(lo);
	}
}
```


### 2.浮点型

**演示浮点型的Demo**
#### 1.DouBle
存储字节 = 8 字节  
```java
public class DouBleDemo{
	public static void main(String[] args){
	Double dou = 12.5D;
		System.out.println(dou);
	}
}
```

#### 2.Float
存储字节 = 4 字节  
```java
public class FloatDemo{
	public static void main(String[] args){
	Float floa = 12.6F;
		System.out.println(floa);
	}
}
```


### 3.字符型

**演示字符型的Demo**
#### 1.Char
存储字节 = 2 字节  
```java
public class CharDemo{
	public static void main(String[] args){
	Char char = '男';
		System.out.println(char);
	}
}
```

### 4.布尔型

**演示布尔的Demo**
#### 1.Boolean
存储字节 = 1 字节
True/False
```java
public class BooleanDemo{
	public static void main(String[] args){
	Boolean b = ture;
		System.out.println(b);
	}
}
```
