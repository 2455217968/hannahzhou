# 周卉涵个人网页草稿

这个文件夹是可以发布到公网的个人网页版本，也可以作为以后继续修改的草稿。

## 文件说明

- `index.html`：网页主体。以后要改文字、顺序、样式，主要改这个文件。
- `portrait.jpg`：首页证件照。换照片时保持文件名不变，或同步修改 `index.html` 里的图片路径。

## 本地预览

直接双击 `index.html`，或在浏览器里打开这个文件即可预览。

## 推荐发布方式

### 方式一：GitHub Pages

适合长期放在简历里，链接稳定，也方便之后更新。

1. 登录 GitHub，新建一个公开仓库，例如 `hannahzhou-site`。
2. 上传本文件夹里的 `index.html` 和 `portrait.jpg`。
3. 进入仓库 `Settings` -> `Pages`。
4. 在 `Build and deployment` 中选择 `Deploy from a branch`。
5. 选择 `main` 分支和 `/root` 目录，保存。
6. 等待几分钟后，会得到类似下面的链接：
   `https://你的用户名.github.io/hannahzhou-site/`

### 方式二：Netlify Drop

适合最快生成一个可分享链接。

1. 打开 Netlify Drop。
2. 把整个 `resume-site-draft` 文件夹拖进去。
3. Netlify 会生成一个 `https://...netlify.app` 链接。
4. 之后如需更新，修改本地文件后重新上传整个文件夹。

## 简历里建议放法

可以写成：

个人主页：`https://...`

或英文简历中写：

Portfolio: `https://...`
