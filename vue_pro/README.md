## 标准化基础项目包

- api：所有后端接口交互的ajax请求放在这里
- assets：资源分类，分为了图片和字体等
- config：项目的一些配置放在这里
- directive：放置vue的自定义指令
- lib->utils.js：与业务结合的方法，放置在这里
- lib->tool.js：与业务没有耦合的，纯粹的工具方法函数放置在这里
- router：路由文件的剥离，index.js中创建路由实例和全局路由守卫，router.js中创建路由列表
- store(Vuex)：状态管理放置在这里，项目最基础的状态都独立拆出文件放置：actions.js、mutations.js、state.js，随着业务的复杂，可以将模块独立出来，比如用户相关的（用户名、用户信息等）状态管理，我们放置在user.js 
- components：组件管理
- views：视图管理

tips: 没有mock
