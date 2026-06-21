# itouLinks

我的連結頁面，部署於 [links.itousouta15.tw](https://links.itousouta15.tw)

## 結構

```
itouLinks/
├── index.html      # 主頁面
├── style.css       # 樣式
├── favicon.ico
├── CNAME
└── img/
    ├── SCAICT.svg
    └── DLHIT.svg
```

## 客製化

### 背景圖片

在 `style.css` 頂端修改 `--bg-image`：

```css
--bg-image: url("your-image.jpg");  /* 預設為 none */
```

套用後為全版固定背景，透明度由 `--bg-opacity` 控制（預設 `0.05`）。

## 技術

- 純 HTML + CSS，無框架
- [Font Awesome 6](https://fontawesome.com/) 圖示
- [Mulish](https://fonts.google.com/specimen/Mulish) 字型（Google Fonts）
- GitHub Pages 部署
