# OurNotes Live2D 创意工坊版

本仓库维护 OurNotes 的 Live2DViewerEX 创意工坊版本。角色目录包含模型、衣装、动作、表情、语音和区域触发配置。

按乐队浏览封面、衣装数量和单角色 WPK。下载后可在 Live2DViewerEX 或 LuvPet 导入。[角色封面介绍](workshop/SHOWCASE.md) · [GitHub 发布](https://github.com/jiangyunxi222/OurNotesLive2D-Workshop/releases/latest)

## 交互

点击头部切换表情，脸部播放语音，上身与左右手臂播放动作，腰部换装，下身打开菜单。

菜单包含循环动作、循环语音、循环换装、恢复待机和关闭菜单。三个循环可同时运行，换装等待当前动作和语音结束。恢复待机保留当前衣装。

## 打包资料

`workshop/characters/` 保存每位角色的资料卡、EX Studio 元数据、封面和资源索引。模型入口与资源来源记录在资料卡中。

在仓库根目录运行 `python workshop/validate.py` 检查资料与文件引用。

使用 EX Studio 加载资料卡指定的模型与元数据，并选择对应封面。导出的 WPK 放入 `workshop/build/`。WPK 导入实测与手动发布由条目维护者完成，状态记录在资料卡中。

## 资源来源

模型、贴图、动作和原始音频的权利归原权利人。各角色的 `source-lock.json` 记录对应来源。[OurNotes](https://bdon.moe/)
