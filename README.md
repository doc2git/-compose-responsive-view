# inspiration-responsive-view

  > link: *git@github.com:doc2git/inspiration-responsive-view.git*

  > state: *进入开发期*

  > inspiration: *boostrap*

+ ### 构想:
1.
上面是能让bootstrap，960等响应式设计开发独占全部屏幕的区域。
  + 考虑一个比优雅的实现方式，实现上边页面单独出现**html/css调试控制面板**
2.
下面左边是参考源（设计图，实践较好的代码，或者ui界面）。
  + 关于尺寸的问题，用**transform:scale(arg)**或者类似的css属性来处理,使得该区域占较少的屏幕尺寸。
3.
下面右边是实际的编码区,尝试确保阅读方便。
  + 输入便捷的问题，通过引用CodeMirror的vim模块实现。