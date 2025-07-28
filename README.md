# GitTree
Github项目目录树生成器。输入一个公开的 GitHub 仓库链接，即刻生成优雅的目录结构。

GitTree旨在帮助开发者快速可视化、分享和归档任何公共仓库的结构。 只需粘贴一个GitHub链接，即可生成清晰的目录树。工具不仅支持按文件/文件夹名称和深度进行过滤，还提供了创新的分享功能：一键导出为带有macOS风格窗口的精美图片，或复制为适用于技术文档的Markdown格式。 

该工具完全在前端运行，核心数据通过调用 GitHub 官方的 [REST API (Git/Trees API)](https://docs.github.com/en/rest/git/trees?apiVersion=2022-11-28#get-a-tree) 获取，确保了数据的实时与准确性。
