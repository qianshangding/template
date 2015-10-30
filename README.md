# template
Maven多模块构建J2ee项目

各个子模块的功能：
test-core：所有业务的核心业务逻辑。
test-ad：广告的业务流程
test-res：资源的业务流程
test-terminal：终端的业务流程
test-user：用户的业务流程
test-web：整个项目的web前端操作
test-dao：整个项目的数据层

采用这种方式搭建项目架构清晰，层次清楚，且对日后项目进行水平拆分和垂直拆分都很方便。
