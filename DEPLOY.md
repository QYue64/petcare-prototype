# GitHub Pages 部署指南

## 🚀 快速部署

### 方式一：GitHub Actions 自动部署（推荐）

1. **推送代码到 main 分支**
   ```bash
   cd petcare-project/prototype
   git push origin main
   ```

2. **启用 GitHub Pages**
   - 访问仓库：https://github.com/QYue64/petcare-prototype
   - 进入 Settings → Pages
   - Source 选择 "GitHub Actions"
   - 保存后会自动触发部署

3. **查看部署状态**
   - 访问 Actions 标签页查看部署进度
   - 部署完成后会显示访问 URL

## 📊 访问地址

部署完成后，原型可通过以下地址访问：

- **主地址**: https://QYue64.github.io/petcare-prototype
- **备用地址**: https://qyue64.github.io/petcare-prototype/

## 📱 原型页面清单 (20 个)

### 用户端 (8 个)
1. 登录页 (login)
2. 首页 (home)
3. 服务者列表 (providerList)
4. 服务者详情 (providerDetail)
5. 订单确认 (orderConfirm)
6. 订单列表 (orderList)
7. 订单详情 (orderDetail)
8. 个人中心 (profile)

### 服务者端 (6 个)
1. 首页 (providerHome)
2. 订单列表 (providerOrders)
3. 入驻申请 (providerApply)
4. 服务报告 (providerReport)
5. 收入中心 (providerEarnings)
6. 个人中心 (providerProfile)

### 管理后台 (6 个)
1. 仪表盘 (adminDashboard)
2. 用户管理 (adminUsers)
3. 服务者管理 (adminProviders)
4. 订单管理 (adminOrders)
5. 财务管理 (adminFinance)
6. 设置 (adminSettings)

## 🎨 设计特性

- **三色主题**: 用户端蓝色、服务者端绿色、管理后台深灰
- **页面切换动画**: 流畅的过渡效果
- **加载动画**: 提升用户体验
- **Toast 反馈**: 操作即时反馈
- **移动端适配**: 响应式设计

## 🔧 故障排查

### 部署失败
1. 检查 GitHub Actions 日志
2. 确认 workflow 文件语法正确
3. 确认仓库有 Pages 权限

### 页面 404
1. 等待 2-5 分钟让 CDN 生效
2. 检查是否部署到正确分支（main 或 gh-pages）
3. 清除浏览器缓存后重试

## 📞 需要帮助？

- GitHub Pages 文档：https://docs.github.com/en/pages
- 项目 Issues: https://github.com/QYue64/petcare-prototype/issues
