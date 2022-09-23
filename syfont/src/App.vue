<template>
  <!--
    (1)APP.vue是主组件,页面入口文件,vue页面资源的首加载项,可理解为所有路由都是app.vue的子组件.
    (2)构建SPA(单页应用)时,方便指定路由对应的组件,如视图层<router-view/>后,路由定义component:Foo.
    -->
  <router-view/>
</template>

<style>
#app {
  font-family: Calibre,
    -apple-system,
    BlinkMacSystemFont,
    Segoe UI,
    Helvetica,
    Arial,
    sans-serif !important;
    display:flex;
}
</style>
