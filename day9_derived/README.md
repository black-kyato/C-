1. 编写一个圆类Circle，该类拥有： 
① 1个成员变量，存放圆的半径；
② 两个构造方法
Circle( )                将半径设为0           
Circle(double  r )      创建Circle对象时将半径初始化为r      
③ 三个成员方法              
double getArea( ) 获取圆的面积            
double getPerimeter( )  获取圆的周长              
void  show( )           将圆的半径、周长、面积输出到屏幕 

编写一个圆柱体类Cylinder，它继承于上面的Circle类，还拥有： 
① 1个成员变量，圆柱体的高；
② 构造方法           
Cylinder (double r, double  h)  创建Circle对象时将半径初始化为r         
③ 成员方法
double getVolume( )    获取圆柱体的体积             
void  showVolume( )    将圆柱体的体积输出到屏幕  

编写应用程序，创建类的对象，分别设置圆的半径、圆柱体的高，
计算并分别显示圆半径、圆面积、圆周长，圆柱体的体积。

2. 构建一个类person，包含字符串成员name（姓名），整型数据成员age（年龄），成员函数
display（）用来输出name和age。构造函数包含两个参数，用来对name和age初始化。

构建一个类employee由person派生，包含department（部门），实型数据成员salary（工资）,
    成员函数display（）用来输出职工姓名、年龄、部门、工资，其他成员根据需要自己设定。

    主函数中定义3个employee类对象，内容自己设定，将其姓名、年龄、部门、工资输出，并计算他们的平均工资。

    3. 魔兽世界之二:装备版
    http: cxsjsxmooc.openjudge.cn/2018t3springw5/3/

    通过阅读题目，构建武士的继承体系
