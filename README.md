
# backbone学习总结

 1. mvc （m：数据 c：控制器 v：视图）
 2. backbone的模块
    event：事件驱动方法（events是backbone中所有其他模块的基类，model、collection、view、router、history继承了events中的方法）
    model：数据集合
    collection：模型集合器
    router：路由器（hash）
    history：开启历史管理
    sync：同步服务器模式
    view：视图（含事件行为和渲染页面）
 3. underscore库（backbone必须依赖的库）
    一些数组，对象，事件的常用方法，针对模型和集合。
 4. jQuery（虽然不是必须依赖，但是可以针对视图实现一些具体的效果）
 5. 基本使用
    直接创建对象
    给构造函数添加实例方法和静态方法
        使用extend改写模型的构造函数
        entend的第一个参数是扩展实例方法
        二参是扩展静态方法
 6.default：{}默认的参数
    initialize：初始化构造函数

     