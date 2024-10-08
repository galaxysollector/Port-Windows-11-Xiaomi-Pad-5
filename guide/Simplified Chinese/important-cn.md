<img align="right" src="https://raw.githubusercontent.com/erdilS/Port-Windows-11-Xiaomi-Pad-5/main/nabu.png" width="425" alt="Windows 11 Running On A Xiaomi Pad 5">

# 在小米平板 5 上安装 Windows

## 重要说明 / 警告
> 尽管目前小米平板 5 在可刷入 Windows 的安卓设备中的支持情况和稳定性属于第一梯队，但仍然存在一些罕见问题，可能严重影响到你的设备。在刷入 Windows 前请务必充分了解这些问题。

## 24H2 EDL (9008) 问题
如果你在任何 24H2 版本中创建还原点或用 diskpart / 磁盘管理器修改任何分区（即使是在外部设备上）后重新启动平板，你的平板将会进入 EDL (9008) 模式。目前尚不清楚是什么导致了这个问题，但它会发生在任何 WoA 设备上，不仅限于小米平板 5。

如果你真的想使用 24H2:

- **不要创建系统还原点** 或使用会创建还原点的软件。
- **不要使用磁盘管理器** 创建、编辑、格式化或修改任何分区。即使是外部设备也不行。
- 即使你尽力避免这样做，请注意，在某些情况下，即使避免了之前提到的任何事情，也有人的平板被送进了 9008！

## 白线问题
在某些极其罕见的情况下，你的平板在 Windows 进入睡眠模式后，屏幕上会显示一些白线。这是由于小米出厂时配备了不兼容的显示配置而导致的硬件问题。

如果你在 Windows 中进入睡眠模式后看到白线，**请立即重启设备！** 如果这些白线在屏幕上停留太久，它们可能会永久存在，无法消除。

目前，解决方案要么是永远不要在 Windows 中让你的设备进入睡眠模式，要么就是把你的平板出掉，然后买一个新的。



















