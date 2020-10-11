# 三大问题
1. gorm是什么？
- go语言编写的ORM框架，支持主流数据库MySQL、PostgreSQL。
    - ORM框架：对象关系映射，采用元数据来描述细节。
        - 元数据：描述其他数据的数据。

2. gorm能做什么？
- 连接数据库，对数据进行操作，与数据库交互。

3. gorm怎么使用？
- 安装gorm和数据库包
    ```
    go get -u gorm.io/gorm
    go get -u gorm.io/driver/sqlite
    ```
- 编写.go进行与数据库交互
    ```
    xxx
    ```