# c3-maps

## julius

`julius/` 目录保存 Julius 地图文件（`.map`），GitHub Pages 会发布：

- 原始 `julius.list`
- 整个 `julius/` 目录中的地图文件
- 一个简单的下载入口页

`julius.list` 在发布时自动生成，每行格式为：

```
文件名 sha256
```

访问地址：

```
https://c3fan.github.io/c3-maps/
https://c3fan.github.io/c3-maps/julius.list
https://c3fan.github.io/c3-maps/julius/<文件名>.map
```

每次向 `main` 分支推送 `julius/` 目录或 `/home/runner/work/c3-maps/c3-maps/.github/workflows/julius-list.yml` 的变更时，GitHub Actions 会自动重新生成 `julius.list`，打包整个 `julius/` 目录，并发布到 GitHub Pages。
