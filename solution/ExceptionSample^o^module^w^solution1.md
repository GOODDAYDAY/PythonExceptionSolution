* 类型
    * ExceptionSample

* 关键字
    * module

* 报错情形描述
    * 一、错误的样例

* 解决方案

  * 1.应在调用对象前保证其初始化完毕

  * 2.在调用对象前先判断是否为null

    ```python
    node = get_node()
    
    if not node:
        do_none_node()
    else:
        do_node

    ```