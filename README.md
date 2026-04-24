# 研究型网页简历（王硕）

这是一个可直接部署的纯静态网页项目，主题为：

**面向无人平台自主感知的研究型工程师**

网页内容已结合论文《先验信息引导下的地面无人平台环境感知技术研究》完成整理，并补充了：

- 邮箱：1972178768@qq.com
- 电话：19871938445
- GitHub：<https://github.com/MichealRW/PGP-DOR>
- 多组实验效果索引
- 框架图示画廊
- 交互式实验结果面板

## 文件结构

```text
web_resume_project/
├── index.html
├── README.md
├── favicon.svg
└── assets/
    ├── f1-7-kuangjia.png
    ├── f2-1-framework.png
    ├── f2-12-structure-pipeline.png
    ├── f2-18-slam-gps.png
    ├── f2-19-map-compare.png
    ├── f3-1-terrain-framework.png
    ├── f3-12-all-dataset-terraineva2.png
    ├── f3-13-all-dataset-terraineva-ele.png
    ├── f3-14-all-dataset-prior-eva.png
    ├── f3-15-all-dataset-prior-xiaorong.png
    ├── f3-16-all-dataset-prior-terrainchange.png
    ├── f3-5-priorguided-pipline.png
    ├── f3-8-traversability-pipeline.png
    ├── f4-1-evolution-framework.png
    ├── f4-10-eval-all-dataset.png
    ├── f4-13-all-study.png
    ├── f4-15-changedetection-frame.png
    ├── f4-16-changedetection-map.png
    ├── f4-2-dynamic-framework.png
    └── f4-4-changedetection-framework.png
```

## 已包含的主要模块

1. 首页概览与个人信息
2. 三个代表性研究贡献卡片
3. 交互式实验结果面板
4. 实验效果索引
5. 框架图示画廊
6. 履历信息与技术关键词
7. 联系信息

## 本地预览

在该目录执行任意静态服务器，例如：

```bash
python -m http.server 8000
```

然后在浏览器打开：

```text
http://localhost:8000/
```

## 部署到 GitHub Pages

1. 新建仓库
2. 将本目录全部文件上传到仓库根目录
3. 在 GitHub 仓库设置中开启 Pages
4. 选择 `Deploy from a branch`
5. 选择 `main` 分支与 `/root`
6. 等待站点生成

## 备注

当前版本不依赖前端框架，便于直接复制、修改和部署。后续如需升级为 React / Vite、Next.js 或双语版本，可在现有结构上继续扩展。
