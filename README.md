# mybatis-list-param
mybatis插件，为mysql支持参数为Iterable或者数组的情况，自动将in(#{list})转换成in(?, ?, ?)的形式，不需要再写forEach或者SqlProvider<br>

使用时，在mybatis的配置文件中添加一个插件cn.yxffcode.mybatis.ListParameterResolver
