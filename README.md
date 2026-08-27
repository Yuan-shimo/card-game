# GitHub Pages 版本

把 `index.html` 和整个 `assets` 文件夹一起放到仓库根目录。

目录结构：

```
card-game/
├─ index.html
└─ assets/
   └─ avatars/
      ├─ avatar-1-02b1108d.png
      ├─ avatar-2-a2603c90.png
      ├─ avatar-3-8c5b7881.png
      ├─ avatar-4-3cade4dc.png
```

头像是从原 HTML 的 Base64 中无损提取出来的原始 PNG，没有重新压缩或降质。
`index.html` 使用相对路径读取图片，因此部署到 GitHub Pages 后会自动从同一仓库加载。
