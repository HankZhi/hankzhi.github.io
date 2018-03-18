## 智今
### 使用
- 切到dev分支
- **编写**博文
- 运行`hexo server`预览
- 运行`hexo deploy`部署  

### 编写
- `front-matter`——文章参数配置
- 标签插件——可生成相应的html块
- 资源文件夹——管理资源
- 数据文件夹——提供一个数据文件,可在文章中使用数据  

### 样式
- 可以在`./themes/simpleblock/styles.css`中修改
- 亦可修改主题中的jade文件的代码逻辑实现组件的展示与否

### 配置
- 总共写了两层配置,`./_config.yml`与`themes/simpleblock/_config.yml`
- 负责生成文章标题的`new_post_name`在`./_config.yml`配置中  

### 注意
- 执行`hexo server`可以在本地浏览器预览
- 执行`hexo deploy`会自动将编译好的代码push到该项目的master分支上,所以不要在master分支上做修改
- 博文以及其他命令参考hexo官方文档  

### markdown语法
- 换行是两个空格加换行  

