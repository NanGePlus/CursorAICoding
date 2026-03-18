# Cursor + RuoYi(若依) 

本期视频为大家分享的是：全栈开发界的「航母战斗群」，Cursor+RuoYi(若依)。一镜到底：聊天式编程，看我如何1小时从0到1撸出高可用的后台管理系统。全民全栈时代，每个人都是自己的CTO            

涉及到的操作说明文档等全部资料都是开源分享给大家的，大家可以在本期视频置顶评论中获取免费资料链接进行下载               

Cursor 是专为提升开发生产力而设计的一款 AI 编程工具              

RuoYi(若依框架) 是基于SpringBoot、Spring Security、Jwt、Vue的前后端分离的免费开源的后台管理系统框架          

- RuoYi(若依)官方网址：https://www.ruoyi.vip/                
- RuoYi(若依)官方文档网址：https://doc.ruoyi.vip/ruoyi-vue/            


## 1 部署和构建

先Plan再Agent，Prompt：            
帮我在本项目中部署和构建RuoYi-Vue3分离版本                
RuoYi-Vue分离版本官方文档：https://doc.ruoyi.vip/ruoyi-vue/                
RuoYi-Vue3代码下载：https://gitcode.com/yangzongzhuan/RuoYi-Vue3             
RuoYi-Vue-Boot-3.x代码下载：https://gitee.com/y_project/RuoYi-Vue/tree/springboot3    

```bash
# 启动后端服务：
cd ruoyi/ruoyi-admin
mvn -DskipTests spring-boot:run
# 启动前端服务
cd ../../ruoyi-ui
npm run dev
```

## 2 开发一个功能模块

### 2.1 创建编码规则

**Prompt：**               
/create-rule 仔细阅读当前这个项目，我后面需要基于这个项目进行迭代开发，帮我写一个规则，用来指导我后续的迭代编码

### 2.2 新增一个菜单

**先Plan再Agent，Prompt：**                              
在系统管理的菜单管理中新增一个目录，目录名字叫：学生管理，再在学生管理这个菜单目录下新建一个菜单叫：学生信息。学生信息菜单具体需要实现的功能是：学生信息列表及管理，包含学号、姓名、身份证号、年龄、性别、年级、班级等字段，支持增删改查和批量导出      

### 2.3 再新增一个菜单

**先Plan再Agent，Prompt：**                              
在学生管理这个菜单目录下再新建一个菜单叫：学生成绩。学生成绩菜单具体需要实现的功能是：学生成绩列表及管理，包含：学号、姓名、语文成绩、数学成绩、英语成绩、成绩总和等字段，支持增删改查和批量导出。学号和姓名来源于学生信息表中的学号和姓名，新增时通过下拉选择学号，下拉选择以学号_姓名展示，如：2026014158_张三丰。          

### 2.4 前端一些调整

**其他一些调整，Prompt：**                   
把菜单首页展示的内容进行调整，先只保留一个欢迎页面，不要有任何其他信息。页面内只展示：欢迎【用户名】来到管理后台            
将菜单导航栏上面的Github快捷入口隐藏              
将菜单导航栏上面的文档快捷入口隐藏              
把平台的logo换成我上传的这张图片                  
把浏览器标签栏上面的logo也换成这个        
把平台名称由 若依管理系统 改为 南哥管理系统              
