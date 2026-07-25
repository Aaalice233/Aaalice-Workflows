这次找到真正的原因了。上次我修的 .publish-wizard label 其实是死代码——发布界面重构成三阶段
 控制台后，DOM 里已经没有 .publish-wizard，实际生效的是另一条同样会把 label 变 grid 的规则
 .publish-console-shell label（style.css:1954）。

 已修改：

 1. .publish-console-shell label → .publish-console-shell label:not(.cover-picker)，封面按
    钮恢复自己的 flex 横向布局；
 2. 顺手删掉了两条已无 DOM 对应的 .publish-wizard 死规则。

 前端测试 9 个通过，生产构建完成，已确认打包产物里只剩 :not(.cover-picker) 版本、没有其他规
 则能再把它压成竖排。

 静态文件直接从磁盘读取，不用重启 ComfyUI，在页面里 Ctrl+F5 强制刷新一下就能看到图标和文字
 并排了。确认显示正常后我再帮你提交这次修复。