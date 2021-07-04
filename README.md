# 2.1 - Beta README

## Memocast

<img title="" src="memocast://memocast.app/588b0160-47e1-11ea-8e5a-551dd9ea6eaa/2a101d00-dbfd-11eb-8236-9fc65697fe39/1625317634557-657.png" alt="linux-512x512.png" data-align="center" width="192">

---

### Quasar + Electron + Muya + Monaco + WizNote = ？

> 此处应有一段Slogon

不知道你是否有和我一样的烦恼，在用 Typora 的时候想要有在线笔记的能力，用在线笔记的时候能有 Typora 一样的编辑能力，虽然说 Typora 和很多的第三方应用集成之后也能达到很棒的写作效率，例如结合 Git 进行笔记版本管理，结合 PicGo 实现笔记图片管理，或者是使用 Typora 作为笔记编辑器，编辑为知笔记。但这些还是太割裂了，不是吗？如果有得选，谁不想要一个可以 All in 的笔记软件呢？

于是，Memocast 诞生了。

<img src="memocast://memocast.app/588b0160-47e1-11ea-8e5a-551dd9ea6eaa/2a101d00-dbfd-11eb-8236-9fc65697fe39/1625318186928-bxa.png" title="" alt="" data-align="center">

写代码的时候会疑惑，会怀疑自己，为什么要花这么多时间去做一个笔记软件，为知官方甚至已经推出了新的编辑器 WizLite ，其对Markdown的支持已经完全跟上了主流水平，甚至有所超出，而且公司成建制的开发能力必定要强于我个人，那为什么还要做，还要投入时间。

想了很多次，**最终**答案大概就是我可以，我想试试，我想要更强的掌控能力，我希望整个记录的流程都掌握在我自己手上。

人生难得几回创造的热情，故事便开始了。

---

### Tech Stack

- Quasar Vue Framework (Vue 2)

- Electron 9.4.0

- Muya (Migrate from marktext (MIT Lisence))

- Monaco (VS Code's Editor)

---

### Feature

1. 较为完整的为知服务的支持。
   
   1. 笔记增删查改
   
   2. 文件夹增删
   
   3. 笔记导出成PNG、Markdown
   
   4. 笔记文件夹批量导出Markdown
   
   5. 支持为知图片服务
   
   6. 笔记标签增删查改
   
   7. 私有化部署服务器的支持

2. 良好的 Markdown 编辑器体验
   
   1. 按下 @ 快捷输入
      
      <img title="" src="memocast://memocast.app/588b0160-47e1-11ea-8e5a-551dd9ea6eaa/2a101d00-dbfd-11eb-8236-9fc65697fe39/1625319074540-jod.png" alt="" data-align="inline" width="418">
   
   2. 完整的快捷键支持，并在 macOS 下支持菜单和帮助查询。
   
   3. 将为知的网页剪辑笔记轻松转换为可阅读的 Markdown 文件
   
   4. 良好的图片支持，支持为知图片，支持 PicGo 上传图片，支持本地图片
   
   5. 相比 marktext ，编辑器做了很多的优化和本地化
   
   6. 支持笔记目录，支持目录跳转
   
   7. 支持流程图，vega 图，mermaid 图等等
   
   8. 笔记锁定模式，锁定之后键盘无法输入，减少误触
   
   9. 所见即所得，良好输入体验

3. 强大的源代码模式
   
   1. 使用 Monaco 作为源代码编辑器
   
   2. 使用 `CmdOrCtrl + Shift + .` 快捷切换源代码模式和 markdown 模式
   
   3. 语法高亮
      
      <img src="memocast://memocast.app/588b0160-47e1-11ea-8e5a-551dd9ea6eaa/2a101d00-dbfd-11eb-8236-9fc65697fe39/1625319462696-tnk.png" title="" alt="" width="519">
   
   4. 侧边栏预览

4. 完整开源， 项目 All in Github， 在网络畅通的情况下可以使用内置的自动更新，快速将软件更新到最新版。


