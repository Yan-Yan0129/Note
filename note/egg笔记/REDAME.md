# egg笔记
    1.要求node.js版本必须大于8.0并且要用LTS版本
    
    2.创建egg环境 npm i egg-init -g /cnpm i egg-init -g (只需要安装一次)

    3.创建egg项目
    （1.）cd到目录里面 （注意不要用英文 不要有空格）
    （2.）egg-init 项目名称 --type=simple 
    例：egg-init eggdemo01 --type=simple
    (3)cd eggdemo01
    (4.)cnpm install (安装依赖)
    （5.）npm run dev(运行项目)

###MVC

>EGG  是一个MVC的框架

>views 视图 模板 页面展示

>controller控制器 负责处理一些业务逻辑的处理

>mdoel 模型 （service） 和数据打交道  (查询数据库 请求数据)
