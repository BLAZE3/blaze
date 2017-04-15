本系统为软院校友管理平台

具有三个模块
    schoolmate-web : 校友用户与本系统交互的前后端模块。主要是controller
    schoolmate-admin : 管理员用户与本系统交互的前后端模块。主要是controller
    schoolmate-core : 数据交互模块，负责提供与数据库交互的一系列功能。主要是service,dao等基础性模块

    web模块和admin模块依赖core模块。web和admin这两个模块单独部署war,都引入core模块的jar

本系统采用 mysql5.6,springmvc4.0+,jdk1.7,mybatis3,redis2.8.3+,tomcat7
项目部署环境：linux
   开发工具：idea/eclipse

note: 所提交所有代码必须格式化。
      所有方法都写注释。
      个人的开发工具的配置文件不需要提交至git。
      git提交comment格式：
         feat：新功能（feature）
         fix：修补bug
         docs：文档（documentation）
         style： 格式（不影响代码运行的变动）
         refactor：重构（即不是新增功能，也不是修改bug的代码变动）
         test：增加测试
         chore：构建过程或辅助工具的变动

      schoolmate 的 doc文件夹 包含3个文本:
          interface.txt ==> 接口文档
          scheme.sql    ==> 数据文件
          note.txt      ==> 备注说明



