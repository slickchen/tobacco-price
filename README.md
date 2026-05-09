# 🚬 烟草价格查询工具

一个简洁美观的移动端烟草价格查询网页，支持实时搜索和品牌筛选。

## 📱 在线访问

👉 **[点击访问](https://你的用户名.github.io/tobacco-price/)**

## ✨ 功能特点

- 🔍 **实时搜索** - 输入关键词快速查找
- 🏷️ **品牌筛选** - 一键筛选各大品牌
- 📊 **盈亏显示** - 红色上涨/绿色下跌
- 📱 **移动优先** - 完美适配手机浏览
- ⚡ **纯前端** - 无需后端，加载飞快

## 🚀 部署到 GitHub Pages

### 方法一：Fork 部署（推荐）

1. **Fork 本仓库**
   - 点击右上角 `Fork` 按钮

2. **启用 GitHub Pages**
   - 进入你 Fork 的仓库 → Settings → Pages
   - Source 选择 `Deploy from a branch`
   - Branch 选择 `main` / `root`
   - 点击 Save

3. **访问网站**
   - 等待 1-2 分钟
   - 访问 `https://你的用户名.github.io/tobacco-price/`

### 方法二：手动创建

1. 新建 GitHub 仓库，命名为 `tobacco-price`
2. 上传 `index.html` 文件
3. 启用 GitHub Pages（同上）

## 📝 更新价格数据

编辑 `index.html` 文件中的 `tobaccoData` 数组：

```javascript
const tobaccoData = [
    {name: "品牌名", category: "分类", price: 价格, profit: 盈亏},
    // 添加更多...
];
```

## 📋 数据格式

| 字段 | 说明 | 示例 |
|------|------|------|
| name | 产品名称 | "芙蓉王(硬蓝)" |
| category | 品牌分类 | "芙蓉王" |
| price | 当期价格 | 208 |
| profit | 盈亏金额 | -10.36 |

## 🎨 自定义样式

修改 `<style>` 标签中的 CSS 变量可调整主题色：

```css
--primary: #ffd700;    /* 金色 */
--up: #ff6b6b;         /* 上涨红色 */
--down: #51cf66;       /* 下跌绿色 */
```

## 📄 许可证

MIT License - 自由使用和修改

---

**免责声明**：本工具价格数据仅供参考，实际交易请以市场为准。