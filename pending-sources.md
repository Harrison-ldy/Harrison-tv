# 暂未加入的影视源

更新日期：2026-10-10

这是此前检索发现的 8 个新增源中，尚未加入个人 XPTV 订阅的 6 个。爱电影、枫叶影院已于本次加入 `all.json`，不再列入候选。此文件仅作备忘，不是订阅文件，也不会自动启用任何源。

来源：[xiaobaitulele/xptv 的订阅清单](https://github.com/xiaobaitulele/xptv/blob/main/main/all.json)。以下配置为记录时的上游快照；以后加入前需重新核对上游地址。未验证实际播放、速度或稳定性。

| 暂未加入的源 | 备注 |
| --- | --- |
| [兔]美剧2046🎬️ | 未实测播放 |
| [兔]瓜子app🎬 | 与已加入的瓜子、瓜子web为不同适配；未实测播放 |
| [兔]欧飞影音(限台湾播放)www.ofiii.com🎬 | 上游标注：限台湾播放；未实测播放 |
| [兔]2k动漫(无搜索)🌸 | 上游标注：无搜索；未实测播放 |
| [兔]路漫漫(无搜索)🌸 | 上游标注：无搜索；未实测播放 |
| [兔]11KT🌸 | 未实测播放 |

## 配置备份

```json
{
  "sites": [
    {
      "name": "[兔]美剧2046🎬️",
      "type": 3,
      "api": "csp_meiju2046_tu",
      "ext": "https://ghp.xptvhelper.link/https://raw.githubusercontent.com/xiaobaitulele/xptv/refs/heads/main/vod/meiju2046_tu.js"
    },
    {
      "name": "[兔]瓜子app🎬",
      "type": 3,
      "api": "csp_guaziapp_tu",
      "ext": "https://ghp.xptvhelper.link/https://raw.githubusercontent.com/xiaobaitulele/xptv/refs/heads/main/vod/guaziapp_tu.js"
    },
    {
      "name": "[兔]欧飞影音(限台湾播放)www.ofiii.com🎬",
      "type": 3,
      "api": "csp_ofiii_tu",
      "ext": "https://ghp.xptvhelper.link/https://raw.githubusercontent.com/xiaobaitulele/xptv/refs/heads/main/vod/ofiii_tu.js"
    },
    {
      "name": "[兔]2k动漫(无搜索)🌸",
      "type": 3,
      "api": "csp_2ksp_tu",
      "ext": "https://ghp.xptvhelper.link/https://raw.githubusercontent.com/xiaobaitulele/xptv/refs/heads/main/vod/2ksp_tu.js"
    },
    {
      "name": "[兔]路漫漫(无搜索)🌸",
      "type": 3,
      "api": "csp_lumm85_tu",
      "ext": "https://ghp.xptvhelper.link/https://raw.githubusercontent.com/xiaobaitulele/xptv/refs/heads/main/vod/lumm85_tu.js"
    },
    {
      "name": "[兔]11KT🌸",
      "type": 3,
      "api": "csp_11kt_tu",
      "ext": "https://ghp.xptvhelper.link/https://raw.githubusercontent.com/xiaobaitulele/xptv/refs/heads/main/vod/11kt_tu.js"
    }
  ]
}
```

## 维护约定

- 后续检索发现的新源，未经确认加入订阅的，记录在本文件中。
- 用户确认加入后，从候选清单移除，更新日期；加入前重新核对上游配置。
- 用户明确删除或放弃的源不自动放回候选；本次删除的趣盘搜不列入。
- 仅在用户要求检查或更新时手动维护，未设置定时检查或自动添加。
