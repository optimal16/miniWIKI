## 1.caffe框架简介
****
### caffe依赖库  
> boost库  
>> &ensp;&ensp;boost是一个C++的库，用途很广，在caffe中主要用到了智能指针、计时器、随机数产生器等。  

> cuda库   
>> &ensp;&ensp;NVIDIA公司推出的基于NVIDIA显卡的GPU计算接口，大大提高计算速度。

> blas库
>> &ensp;&ensp;Basic Linear Algebra Subprograms,即基础线性代数子程序库，提供了各种加速向量和矩阵运算的接口。  
>> &ensp;&ensp;在caffe中有atlas、openblas、mkl等选择。（blas/lapack是接口规范，相关库还有acml,cublas）