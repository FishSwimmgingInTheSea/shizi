# 拾字

拾起一闪而过的念头。

拾字是一款 Windows 本地 Markdown 笔记。打开就能写，停下自动保存。笔记是明文 `.md`，存在你自己的电脑上。

## 下载

在 [Releases](https://github.com/FishSwimmgingInTheSea/shizi/releases/latest) 下载 `拾字_0.1.1_x64-setup.exe`，双击安装。

安装时如果 Windows 提示「已保护你的电脑」，点「更多信息」，再选「仍要运行」。

- Windows 10 1809+ 或 Windows 11（64 位）
- 需要 [WebView2](https://developer.microsoft.com/microsoft-edge/webview2/)。Windows 11 已自带

## 界面

主窗口：

![主窗口](<img width="2880" height="1698" alt="image" src="https://github.com/user-attachments/assets/418c6eaa-7dca-4069-baa2-c7ed8e91d5e2" />
)

速记小窗：

![速记小窗](<img width="2880" height="1705" alt="image" src="https://github.com/user-attachments/assets/ca2f9a34-d32f-4cac-a549-c23847dd11b8" />
)

## 功能

- 左侧是笔记列表，中间写作，右侧是大纲
- 停止输入大约 1 秒后自动保存，`Ctrl+S` 会立刻保存
- 每篇笔记最多 8 个标签，可以按标签筛选
- ``Ctrl+` `` 唤起置顶速记小窗。小窗可以新写，也可以打开已有笔记
- 主窗口点关闭后留在系统托盘
- 删除的笔记进回收站，可以还原
- 可以换浅色、深色或跟随系统，正文字号 12–20px
- 粘贴或拖入的图片保存在笔记旁边

## 快捷键

| 快捷键 | 作用 |
| --- | --- |
| `Ctrl+N` | 新建笔记 |
| `Ctrl+S` | 立即保存 |
| ``Ctrl+` `` | 唤起速记小窗 |
| `Ctrl+W` | 保存后隐藏窗口 |
| `Esc` | 关闭设置或快捷键表；在速记小窗中收起 |

## 笔记放在哪

默认在 `%APPDATA%\com.notelet.app\notes\`。在设置里可以换文件夹。
