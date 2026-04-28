# 腾讯视频 AI 剧情广告 Demo

## 入口

打开 `index.html` 即可体验。

## 推荐体验路径

1. 点击播放正片。
2. 正片播放到 4 秒左右出现 AI 轻提示。
3. 正片播放到 5 秒进入 AI 剧情广告。
4. AI 识别剧情并播放海天味极鲜 10 秒广告短片。
5. 广告短片结束后停留在可点击结果页。
6. 点击“查看详情”进入商品详情页。
7. 在详情页可“一键购买”，也可点击右上角“退出广告”返回正片继续播放。

## 核心创意

广告不是固定中插，而是根据当前剧情识别出的“番茄翻炒、调味动作、家庭厨房”生成剧情相关广告。  
用户看到的是一个与剧情自然连接的 AI 广告短片，并在结束页获得“AI 鲜味分 82 -> 96”的趣味反馈。

## 静态部署

这是纯静态页面，可直接部署到：

- Netlify：拖拽整个 `tencent-ai-ad-demo` 文件夹到 Netlify Deploys。
- Vercel：导入该文件夹，Framework 选择 Other/Static。
- GitHub Pages：把该文件夹内容放到仓库根目录，Pages Source 选择对应分支。

## 文件说明

- `index.html`：评委入口页，也是腾讯视频播放页 Demo。
- `tencent-video-player-mock.html`：播放器页备用入口。
- `shopping-seasoning-kit.html`：海天味极鲜商品详情页。
- `shopping-fresh-kit.html`：备用食材包详情页。
- `assets/haitian-seasoning-ai-ad.webm`：AI 广告短片。
- `assets/kitchen-cooking-source.mp4`：正片素材。
