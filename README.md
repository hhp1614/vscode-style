## vscode 字体样式设置

> 需要安装「Custom CSS and JS Loader」插件

在 vscode 的 `settings.json` 中设置

```text
https://cdn.jsdelivr.net/gh/hhp1614/vscode-style@版本号/字体名/index.css
https://cdn.jsdelivr.net/gh/hhp1614/vscode-style@版本号/字体名/md.css
```


```json5
// 插件加载的 CSS 文件地址
{
    "vscode_custom_css.imports": [
        "https://cdn.jsdelivr.net/gh/hhp1614/vscode-style@1.2.3/sarasa-fixed/index.css"
    ]
}
```

## markdown 样式设置

在 vscode 的 `settings.json` 中设置 `https://cdn.jsdelivr.net/gh/hhp1614/vscode-style/md.css`

也可以指定版本号：`https://cdn.jsdelivr.net/gh/hhp1614/vscode-style@1.0.0/md.css`

```json5
{
    "markdown.styles": ["https://cdn.jsdelivr.net/gh/hhp1614/vscode-style@1.2.3/sarasa-fixed/md.css"]
}
```