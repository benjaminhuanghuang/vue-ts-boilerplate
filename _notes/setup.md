

## Upgrate to Vue 3
```
  cd vue-next-test
  vue add vue-next
```
执行上述指令后，会自动安装 vue-cli-plugin-vue-next 插件（查看项目代码），该插件会完成以下

安装 Vue 3.0 依赖
更新 Vue 3.0 webpack loader 配置，使其能够支持 .vue 文件构建（这点非常重要）
创建 Vue 3.0 的模板代码
自动将代码中的 Vue Router 和 Vuex 升级到 4.0 版本，如果未安装则不会升级
自动生成 Vue Router 和 Vuex 模板代码
