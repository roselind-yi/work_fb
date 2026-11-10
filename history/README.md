# history

微信视频归档备份。

## 目录结构

```
history/
└── video/
    ├── 2026-09/
    ├── 2026-10/
    └── 2026-11/
```

按月份分目录，每个视频通常包含三个同名文件：

| 文件 | 说明 |
| --- | --- |
| `xxx.mp4` | 视频本体 |
| `xxx_raw.mp4` | 原始画质版本（体积较大） |
| `xxx.jpg` / `xxx_thumb.jpg` | 封面与缩略图 |

## 超 100 MB 的原片

GitHub 单文件上限 100 MB，以下 11 个 `_raw.mp4` 原片（合计约 3.38 GB）无法存入仓库，
已作为附件发布在 Release 中：

**下载地址：<https://github.com/roselind-yi/work_fb/releases/tag/video-archive>**

| # | 文件名 | 大小 | 原目录 |
| --- | --- | --- | --- |
| 1 | `534f88cbbeae79e84cc62ecbf164e6e4_raw.mp4` | 1006.1 MB | 2026-10 |
| 2 | `3eabdd73da0c07287177d7d119975a87_raw.mp4` | 513.1 MB | 2026-10 |
| 3 | `7bbfa799f5af724d7d0b9c5e563e4123_raw.mp4` | 441.7 MB | 2026-10 |
| 4 | `c7d444e01e0e3b87e1e564402402a8fc_raw.mp4` | 339.9 MB | 2026-10 |
| 5 | `1617a7ef0486eacee6b917f9db6db1a9_raw.mp4` | 241.8 MB | 2026-10 |
| 6 | `0664df74a1cc0779a543ac27dc454dbc_raw.mp4` | 191.3 MB | 2026-10 |
| 7 | `95dedb90ace0513100d115b5e8cc2d92_raw.mp4` | 191.3 MB | 2026-10 |
| 8 | `be31d84fbd760e86bb1ffb6096b9293f_raw.mp4` | 148.3 MB | 2026-10 |
| 9 | `f3820965b6a7d6fa230d53c643ec7ec7_raw.mp4` | 144.5 MB | 2026-10 |
| 10 | `e23e52b0978a8cb1ff139fa5fd43d191_raw.mp4` | 137.0 MB | 2026-09 |
| 11 | `42de3f733c9645c73cf281ec434901ea_raw.mp4` | 107.1 MB | 2026-10 |

> 说明：这 11 个文件对应的常规版本 `xxx.mp4` 与缩略图已在 `video/` 目录中，此处仅缺少原始画质版本。
