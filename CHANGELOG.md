# 修改依赖管理部分

此版本主要将pom中dependencies进行了重构，在framework-core中，几乎将所有的dependency都做了dependencyManagement。以后具体的项目或者组件都进行各自pom的依赖管理。但是为了方便，针对springmvc的web项目，则可以使用framework-wrapper项目来做为parent。

新增：

1) 多环境打包支持 

2017/6/1

+ 新增shiro-cas的dependency支持