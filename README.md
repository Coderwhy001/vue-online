1. npm run serve 开发
2. npm run build 准备打包
3. 将dist/index/html 所有的css js 连接改成 ./
上线的代码都在dist 下
4. git checkout -b gh-pages
   删除代码， 九八dist/ 所有代码放到根目录下，
5. git push origin gh-pages
   源码在master分支， 上线的代码在 dist/

1. iview 的from 通过组件和配置的理念， 完爆原生html， css，js写法
组件的魅力 html 标签是平级的
Button -> button 比较
2. Form FormItem i-input Button 组件 表单的UI 文档
3. :model  :rule="" 验证码是配置出来的 