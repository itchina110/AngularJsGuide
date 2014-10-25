AngularJs数据绑定
==============

数据绑定在Angular应用中是model和view组件中的一种数据自动同步。视图是模型任何时候的投影。当模型改变时，相应的变化也会映射在视图上，反之亦然。

      数据绑定在传统模板系统中的表现：
       ![image](http://github.com/ychow/AngularJsGuide/raw/master/img/One_Way_Data_Binding.png)
大多数模板系统里面的数据绑定只是单向的绑定：他们只是把模板和模型合并到视图里面。视图生成后，改变模型或者视图相关的部分都不会自动映射到视图上。更糟糕的是，用户对视图上做的一些改变都不会映射到模型中。这意味着，开发者需要编写代码，来让视图的模型和视图模型快速同步。

      数据绑定在Angular模板系统中的表现：
      ![image](https://raw.githubusercontent.com/ychow/AngularJsGuide/master/img/One_Way_Data_Binding.png)
      
Angular模板就不一样了。      
