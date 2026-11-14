# docs/

这个目录只放 README 用到的图片资源。

| 文件名 | 用途 | 建议尺寸 |
| :-- | :-- | :-- |
| `stars-manager.png` | Stars Manager 项目卡片封面 | 800 × 400 |
| `blog.png` | 避风塘博客封面 | 800 × 400 |
| `ztasking.png` | zTasking 项目卡片封面 | 800 × 400 |
| `ztranslate.png` | zTranslate 项目卡片封面 | 800 × 400 |
| `stars-manager-demo.gif` | Stars Manager 录屏动图 | ≤ 5 MB |
| `ztasking-demo.gif` | zTasking 录屏动图 | ≤ 5 MB |

放好文件后，回到根目录 `README.md`，把对应的 `<!-- ... -->` 注释去掉即可显示。

**录屏建议**：用 ScreenToGif 或 ffmpeg 转成 GIF，控制体积在 5 MB 以内，GitHub 才能正常加载。

```bash
ffmpeg -i demo.mp4 -vf "fps=15,scale=800:-1:flags=lanczos" -loop 0 demo.gif
```
