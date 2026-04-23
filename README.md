# knowledgeDB

> 帅青的个人知识库 · [shuaiqing.xyz](https://shuaiqing.xyz)

一个持续生长的静态知识库站点，收录阅读笔记、长文解读与交互式阅读器。部署于 Hostinger VPS + Nginx + Let's Encrypt。

## 内容分类

| 分类 | 内容 |
|---|---|
| 量化金融 | [量化交易系统全景指南](quant_system_guide.html) |
| AI · 技术 | [LLM 大语言模型全景解析](llm-guide.html) |
| 哲学 · 逻辑 | [逻辑学双典精读 · 交互版](logic-books-reader.html) |
| 历史 · 经典 | [毛泽东选集 · 交互学习版](maozedong-xuanji.html) |
| 学习方法 | [高效学习指南](learning-guide.html) · [通识教育](tongshi-jiaoyu.html) |

## 技术栈

- **前端**：纯静态 HTML / CSS / 少量原生 JS，无构建步骤
- **字体**：Inter + JetBrains Mono（Google Fonts）
- **设计**：Silicon Valley 清亮风格，响应式布局，支持分类筛选
- **部署**：Hostinger VPS（Ubuntu 24.04）+ Nginx + Let's Encrypt SSL
- **域名**：[shuaiqing.xyz](https://shuaiqing.xyz)

## 本地预览

```bash
# 任选一种
python3 -m http.server 8000
npx serve .
```

打开 http://localhost:8000。

## 部署

直接通过 `scp` 同步到 VPS：

```bash
scp *.html root@<vps-ip>:/var/www/shuaiqing.xyz/
```

## 版本

见 [CHANGELOG.md](CHANGELOG.md)。

## 许可

内容为作者个人笔记与摘录，仅供学习交流。
