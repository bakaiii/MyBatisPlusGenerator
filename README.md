# MyBatisPlusGenerator
> 一个自用的基于MyBatis-Plus的逆向工程工具！

## 说明

* 众所周知，Mybatis-Plus 官方提供的有逆向工程。个人觉得功能太强大了，在实际的开发中它自动生成的许多内容都是用不到的，就导致产生许多无用的垃圾代码，而常用的一些东西他反而又没有，因此就有了自己写一个的想法，也就有了此项目！
* 这个逆向工程是根据Mybatis-Plus的逆向工程的进行的自定义，更符合我的使用风格
* 只支持从 数据库->Java



## 待完善

- [ ] 暂只测试并通过了MySQL，其他类型的数据库按理说也可用，因为核心是使用的Mybatis-Plus的逆向工程，但未做测试，因为我用的较多的是MySQL，等我用到其他数据库了再去完善，当然各位有需的也可以自己完善一下



## 推荐数据库命名规则

* 数据库表名：全小写，多个单词以下划线 ```_``` 分割
* 数据库字段名：全小写，多个单词以下划线 ```_``` 分割



## 如何使用

1. 项目仅两个Java文件，一个配置类，一个主程序
2. 在 ```CoreConfig.java``` 中按照所给示例进行配置
3. 然后运行 ```MyBatisPlusGenerator.java``` 的 ```main``` 方法即可！



## 注意

* 建议在生成时不要用联合主键，可能会有问题，可以在生成代码前修改数据库，生成完成后再修改为联合主键

