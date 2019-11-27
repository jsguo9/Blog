<!--
 * @Author: guoxinggang<guoxinggang@gsaxns.com>
 * @Version: 1.0
 * @Date: 2019-10-28 11:15:05
 * @LastEditTime: 2019-10-29 08:41:27
 * @Description: 
 -->
# JavaScript 运算符

#### 一、算数运算符

##### 1、加法运算符

加法运算符（+）对数字相加，例如：

```
var x = 7;
var y = 8;
var z = x + y;
```

##### 2、减法运算符

减法运算符（-）对数字相减，例如：

```
var z = x + y;
var x = z - y;
var y = z - x;
```

##### 3、乘法运算符

乘法运算符（*）对数字相乘，例如：

```
var x = 7;
var y = 8;
var z = x * y; 
```

##### 4、除法运算法

除法运算符（/）对数字相除，例如：

```
var z = x * y;
var x = z / y;
var y = z / x;
```

##### 5、取余运算符

取余运算符（%）对数字取余，例如：

```
var x = z % y;
var y = z % x;
```

##### 6、自增运算

自增运算（++）对数字自增加，例如：

```
var x = 1;
var y = 1;
x = ++1;
y = 1++;

++1和1++的区别：
++1是先自增，再运算/赋值；
1++是先运算，再自增/赋值。
```

##### 7、自减运算

自减运算（--）对数字自减，例如：

```
var x = 5;
var y = 5;
x = --5;
y = 5--;

--5和5--的区别：
--5是先自减，再运算/赋值；
5--是先运算，再自减/赋值。
```

#### 二、赋值运算符

##### 1、赋值运算符

赋值运算符（=）把值赋给变量。例如：

```
var x = 7;		// 向 x 赋值 7
var y = 8;		// 向 y 赋值 8
```

##### 2、加法赋值运算法

加法赋值运算符（+=）向变量添加一个值。例如：

```
x += y；
// x += y相当于x = x + y;
```

##### 3、减法赋值运算法

减法赋值运算符（-=）向变量减去一个值。例如：

```
x -= y；
// x -= y相当于x = x - y;
```

##### 4、乘法赋值运算

乘法赋值运算符（*=）向变量乘以一个值。例如：

```
x *= y；
// x *= y相当于x = x * y;
```

##### 5、除法赋值运算

乘法赋值运算符（/=）向变量除以一个值。例如：

```
x /= y；
// x /= y相当于x = x / y;
```

##### 6、取余赋值运算

取余赋值运算符（%=）向变量取余一个值。例如：

```
x %= y；
// x %= y相当于x = x % y;
```

#### 三、比较运算符

##### 1、等于

```
var x == y;
// x与y等与；
注：只比较值，不比较数类型。
```

##### 2、等值

```
var x === y;
// x与y等值；
注：既比较值，又比较数据类型；
```

##### 3、不相等

```
x != y;
// x与y不相等；
```

##### 4、不等值

```
x !== y;
// x与y不等值；
```

##### 5、大于

```
x > y;
// x大于y；
```

##### 5、小于

```
x < y;
// x小于y；
```

##### 6、大于等于

```
x >= y;
// x大于等于于y；
```

##### 6、小于等于

```
x <= y;
// x小于等于y；
```

##### 7、三目运算符

```
z ？ x :  y;
// 如果x满足条件，就把x赋给z；如果y满足条件，就把y赋给z。
```

#### 四、逻辑运算符

##### 1、逻辑与

```
if(x && y){ // 两个条件都要满足
    console.log(1);
}else{
    console.log(0);
}
```

##### 2、逻辑或

```
if(x || y){ // 两个条件只要满足其中一个就可以
    console.log(1);
}else{
    console.log(0);
}
```

##### 3、逻辑非

```
if(!(x == y)){ // 两个条件都要满足
    console.log(true);
}else{
    console.log(false);
}
```