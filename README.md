## 关于

### 项目名称

背了么(微信小程序)

基于四六级来临之际，背了么(背单词微信小程序)帮助大家共度四六级难关

### 技术栈

`taro`   `taro-ui` `taro-axios`  `redux`  `sass`

### 文件目录

```
|--config                          //各端跨平台开发所需要的单独的配置文件
|--src                                //开发目录  
     |--api                       //项目接口路径
     |--action                    //redux中执行调用函数文件夹
         |--counter.js         //背单词页面
         |--modelAction.js    //首页
         |--review.js                //复习页面
     |--assets                          //静态文件
          |--images                   //存放图片
     |--Component              //相关组件文件夹
          |--done                       //相关板块完成之后提示模块
          |--glossary                //生词本展示模块
          |--Model                    //
          |--remember           //背单词模 块
          |--review                   //复习单词模块
     |--constants                 //redux相关配置srtore文件 
     |--pages                        //页面文件夹
          |--glossary              //生词本页面
          |--index                   //首页
          |--login                    //登录界面
          |--remember         //背单词界面
          |--review                 //单词自检界面
               |--search                 //单词查询界面
          |--reviewrap          //复习类型选择界面
     |--reducers                 //redux配置相关文件夹
     |--static                       //静态文件夹
         |--font                     //引用字体文件夹
|--app.jsx                       
|--app.scss
```

### 接口数据

关于后台接口数据,除查询单词接口来源于百度翻译外,其余的接口数据均来自配套的后台系统

### 项目运行

```
cnpm i            //下载所需要的包
(如若为安装taro,请先安装?taro)
npm run dev:weapp       //启动taro,生成微信小程序文件模板
将项目文件导入到微信开发工具中
```

## 目标功能

- [x] 用户登录                    --完成
- [x] 选择背诵计划            -完成
- [x] 选择单词背诵个数   --完成
- [x] 单词记忆                    --完成
- [x] 单词检测                    --完成
- [x] 生词本                       --完成
- [x] 查询单词                 --完成
- [ ] 排行榜                    --待完成
- [ ] 打卡记录                --待完成
- [ ] 加入学习小组        --待完成
- [ ] 视频教学                --待完成



## 效果演示
