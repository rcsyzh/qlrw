青龙脚本

## GitHub Actions 配置

当前工作流只在指定脚本目录更新时自动维护 README 表格，使用 GitHub Actions 自动提供的 GITHUB_TOKEN 写回仓库，不需要额外 Secret 或 Cloudflare 配置。工作流依赖的 README 表格锚点（README_TABLE_START/END）若被删除，自动更新步骤会失败。
