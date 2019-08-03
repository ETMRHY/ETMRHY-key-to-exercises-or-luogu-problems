浮点数（小数）类型


浮点型的定义有两种

1.double （双精度）

2.float  （单精度）

什么是单精度和双精度呢？

试着执行以下实例

```double
//double
#include<bits/stdc++.h>
using namespace std;
int main()
{
    double a;
    a=3.14159265358979323846264338327950288;
    printf("%lf",a);  //double型用%lf   scanf()函数也一样
    return 0;
}
```

```float
//float
#include<bits/stdc++.h>
using namespace std;
int main()
{
    float a;
    a=3.14159265358979323846264338327950288;
    printf("%f",a);  //float型用%f   scanf()函数也一样
    return 0;
}
```

我们的测试数据是3.14159265358979323846264338327950288  

发现了什么

没错！double中的有效数位（正确输出的数位）更多，其实double型可以输入比float更长的数，这个就自己试一试了

