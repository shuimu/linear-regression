这是linear regression的说明文档

1.  输入文件格式

    <1> 训练集文件train_file:
    以\t分割，第一列为instances, 然后依次是feature1,feature2,feature3,...,featuren, 最后是target
    eg:    
    ---------------------------------------------
    aaa1    10  9   3   11
    aaa2    11  7   4   12
    bbb1    8   11  9   9
    bbb3    12  -10 4   118
    ...
    kkkz    0   12  -1  -33
    ---------------------------------------------


    <2> 测试集文件test_file:
    以\t分割，第一列为instances, 然后依次是feature1,feature2,feature3...
    eg:
    ---------------------------------------------
    aaa1    10  9   3
    aaa2    11  7   4
    bbb1    8   11  9
    bbb3    12  -10 4
    ...
    kkkz    0   12  -1
    ---------------------------------------------


2.  使用命令
    --------------------------------------------------     
    ./lr -n 10 -a alpha -t train_file -i test_file -o output 
    --------------------------------------------------

2.  求参方法
    lr使用batch gradient descent的策略


3. 其他
    auther: shuimuxixiha
    email:  1141482126@qq.com
    phone:  15300064077
