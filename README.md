# c3-maps

## julius

`julius/` 目录保存 Julius 地图文件（`.map`）。

`julius.list` 为自动生成文件，每行格式为：

```
文件名 sha256
```

该文件通过 GitHub Pages 对外提供，访问地址：

```
https://c3fan.github.io/c3-maps/julius.list
```

每次向 `main` 分支推送 `julius/` 目录变更时，GitHub Actions 会自动重新生成 `julius.list` 并更新仓库及 GitHub Pages。