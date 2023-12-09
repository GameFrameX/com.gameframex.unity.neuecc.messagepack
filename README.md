# 非常强大的C# 序列化和反序列化库

用于 C# 的极快的 MessagePack 序列化程序。 它比 MsgPack-Cli 快 10 倍，并且优于其他 C# 序列化程序。MessagePack for C# 还内置了对 LZ4 压缩的支持，这是一种非常快的压缩算法。性能非常重要，尤其是在游戏、分布式计算、微服务或数据缓存等应用中。

该库主要服务于 `https://github.com/AlianBlank/GameFrameX` 作为子库使用。


# 使用方式(三种方式)
1. 直接在 `manifest.json` 文件中添加以下内容
   ```json
      {"com.neuecc.messagepack": "https://github.com/AlianBlank/com.neuecc.messagepack.git"}
    ```
2. 在Unity 的`Packages Manager` 中使用`Git URL` 的方式添加库,地址为：https://github.com/AlianBlank/com.neuecc.messagepack.git

3. 直接下载仓库放置到Unity 项目的`Packages` 目录下。会自动加载识别

# 改动功能

1. 增加 `Packages` 的支持
2. 修改语法版本为C# 7.0 


# 使用文档
https://github.com/MessagePack-CSharp/MessagePack-CSharp

# 同步版本 `2.5.140`

https://github.com/MessagePack-CSharp/MessagePack-CSharp/commit/eefc9079d12c476f95a12ccb4c1a18bf0f9aa03c