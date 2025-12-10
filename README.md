# 🏢 欢迎来到公司知识库

> 内部文档中心 · 技术共享平台 · 最佳实践指南

<div class="dashboard">
  <div class="card">
    <h3><i class="fas fa-rocket"></i> 快速开始</h3>
    <ul>
      <li><a href="/guide/getting-started">新人指南</a></li>
      <li><a href="/guide/development">开发环境配置</a></li>
      <li><a href="/guide/deployment">部署流程</a></li>
    </ul>
  </div>

  <div class="card">
    <h3><i class="fas fa-book"></i> 核心文档</h3>
    <ul>
      <li><a href="/api/">API 文档</a></li>
      <li><a href="/architecture/">系统架构</a></li>
      <li><a href="/database/">数据库设计</a></li>
    </ul>
  </div>

  <div class="card">
    <h3><i class="fas fa-question-circle"></i> 帮助支持</h3>
    <ul>
      <li><a href="/faq/">常见问题</a></li>
      <li><a href="/troubleshooting/">故障排除</a></li>
      <li><a href="/contact/">联系我们</a></li>
    </ul>
  </div>
</div>

## 📈 最近更新

| 文档                               | 更新时间   | 更新内容           |
| ---------------------------------- | ---------- | ------------------ |
| [API认证机制](/api/authentication) | 2024-01-15 | 新增JWT认证说明    |
| [部署指南](/guide/deployment)      | 2024-01-10 | 更新Docker配置     |
| [代码规范](/guide/code-style)      | 2024-01-05 | 新增TypeScript规范 |

## 🚀 快速链接

- 🔗 **在线版本**: [https://wiki.company.com](https://wiki.company.com)
- 💾 **GitHub仓库**: [company/wiki](https://github.com/company/wiki)
- 📧 **反馈建议**: wiki-feedback@company.com
- 📱 **移动端**: 支持响应式设计

## 📚 文档分类

### 技术文档
- [开发指南](/guide/development) - 环境配置、开发流程
- [API参考](/api/) - 接口文档、调用示例
- [架构设计](/architecture/) - 系统架构、组件说明

### 运维文档
- [部署指南](/deployment/) - 生产环境部署
- [监控告警](/monitoring/) - 系统监控配置
- [故障处理](/troubleshooting/) - 常见问题解决

### 团队协作
- [代码规范](/guide/code-style) - 编码规范、最佳实践
- [Git工作流](/guide/git-workflow) - 分支管理、提交规范
- [团队协作](/team/collaboration) - 协作流程、工具使用

## 🎯 如何贡献？

1. **编辑文档**: 在GitHub上编辑Markdown文件
2. **本地预览**: 运行 `npm run serve` 或直接访问
3. **提交更改**: 创建Pull Request
4. **自动部署**: 合并后自动更新在线版本

```bash
# 本地开发预览
git clone https://github.com/company/wiki.git
cd wiki
# 使用任意HTTP服务器启动
python3 -m http.server 8000
# 访问 http://localhost:8000
```

