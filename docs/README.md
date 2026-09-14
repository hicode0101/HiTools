# HiTools 官网（docs/）

本目录即 Jekyll 站点源码，推送到 GitHub 后由 **GitHub Pages 自动构建部署**，线上地址：**https://tools.hicode.top**

## 目录结构

```
docs/
├── _config.yml          # 站点配置（标题、描述、联系方式等）
├── _data/
│   ├── tools.yml        # 工具矩阵数据 —— 新增/修改工具只需编辑此文件
│   └── spotlights.yml   # 「主力装备」精选亮点数据
├── assets/css/style.css # 全站样式
├── images/              # 微信 / 公众号二维码
├── index.html           # 单页模板（Liquid）
└── CNAME                # 自定义域名
```

## 本地开发

环境要求：Ruby 3.4+（本机已安装于 `C:\Ruby34-x64`，含 Jekyll 4.4）。

```bash
cd docs

# 实时预览（修改自动刷新），访问 http://127.0.0.1:4000
jekyll serve

# 或仅构建，产物在 _site/
jekyll build
```

> 注意：
> - 本机网络下 gem 安装需走代理，如重装依赖请先设置 `HTTP_PROXY` / `HTTPS_PROXY`（如 `http://127.0.0.1:7891`）。
> - 本机 Jekyll 未安装 `em-websocket`（该依赖仅在 `jekyll serve --livereload` 时使用，需 MSYS2 编译环境），`jekyll serve` 默认不开 livereload，不影响构建与部署；如需 livereload，运行 `ridk install 3` 安装 MSYS2 后 `gem install em-websocket` 即可。

## 新增工具

编辑 `_data/tools.yml` 按现有格式追加一条即可，首页工具矩阵与跑马灯自动更新；若需重点展示，再在 `_data/spotlights.yml` 中添加亮点条目。

## 部署

推送后 GitHub Pages 自动从 docs/ 构建，无需额外操作。构建产物 `_site/` 已在 `.gitignore` 中排除，请勿手动提交。
