# BFC

## 可以实现 BFC 操作有哪些？

- 根元素（html）

### 作用于子元素创建 BFC

- 浮动元素
- 定位元素

### 作用于父元素创建 BFC

- overflow （不为 visible）
- 行内块元素（inline-block）
- 表单单元格（table-cell）
- 表格标题（table-caption）
- 匿名表格单元格（table、table-row、 table-row-group、table-header-group、table-footer-group）
- 弹性布局（flex、inline-flex）
- 网格布局（grid、inline-grid）
- contain（layout、content 或 paint）
- column-count 或 column-width（不为 auto）
- column-span（all）
