linux_c
=======

linux c study

```conf
越抽象的东西, 把它变具象就好理解了。

char p          //点,         一页纸上的一个字
char *p        //线,         一行字
char **p       //面,         一页字   
char ***p      //空间,     一本书

二维数组

char p[2][3];  //2行3列的数组

char (*q)[3];
//q是一个"行指针",并且每行只有3个字符
//q[0]第一行首地址
//q[1]第二行首地址
//q[2]第三行首地址

char p[2][3]= {"123", "456"};
char (*q)[3]
q = p;

printf("%c\n", p[1][2]); //6
printf("%c\n", *(*(q+1)+2)); //6

```

