# 資產文件夾 (Assets Folder)

此資料夾用於存放所有旅遊相關的圖片素材：

## 📁 建議的目錄結構

```
assets/
├── covers/              # 各行程的封面圖片
│   ├── 202604-fukuoka.jpg
│   ├── 202607-taipei-bib.jpg
│   └── 202609-miyako.jpg
│
├── galleries/           # 行程內的相片庫
│   ├── fukuoka/
│   ├── taipei-bib/
│   └── miyako/
│
└── maps/               # 地圖截圖或地理位置圖
    ├── fukuoka-map.jpg
    ├── taipei-map.jpg
    └── miyako-map.jpg
```

## 📸 使用方式

在 HTML 中引用圖片時，使用相對路徑：

```html
<!-- 從 index.html 引用 -->
<img src="assets/covers/202607-taipei-bib.jpg" alt="雙北美食">

<!-- 從 trips/202607-taipei-bib.html 引用 -->
<img src="../assets/covers/202607-taipei-bib.jpg" alt="雙北美食">
```

## 💡 建議

1. 圖片建議使用 WebP 或 JPG 格式
2. 建議壓縮圖片大小，保持在 500KB 以下
3. 封面圖片建議尺寸：1200x400px 或 1200x600px
4. 相片庫圖片建議尺寸：800x600px 或 600x400px

---

準備好後，直接上傳圖片到對應的子資料夾即可！
