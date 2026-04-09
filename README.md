# 09@LLMWiki-Site

这里存放 LLMWiki 的展示层输出。

原则：
- 原内容在 `08@LLMWiki`
- 展示层在 `09@LLMWiki-Site`
- 两者完全分离
- 展示层只读，不手工改正文

## 预览方式

如果本机已安装 MkDocs：

```bash
cd F:\OneDrive\Obsidian\workRoot\09@LLMWiki-Site
mkdocs serve -f mkdocs.yml
```

如果本机还没有 MkDocs，可以先直接打开 `docs/index.md` 或等后续补齐构建环境。
