# Carpet GUI / 地毯规则图形配置模组

为 Carpet 本体及扩展规则提供图形化配置，支持中文规则名称、按存档保存、导入与导出。

当前版本：**1.0.4**。

## 下载与安装

下载 [carpet-gui-1.0.4.jar](carpet-gui-1.0.4.jar)，移除 `mods` 文件夹中的旧版本，然后放入此文件并重启游戏。

环境要求（来自模组元数据）：

- Minecraft Java **26.1.2**
- Java **25 或更高版本**
- Fabric Loader **0.19.3 或更高版本**
- 适用于 26.1.2 的 Fabric API **0.151.0+26.1.2 或更高版本**
- 支持 26.1.2 的 Carpet **26.1 系列**

不要把源码 ZIP 当作模组安装。安装文件的校验值见 [SHA256SUMS.txt](SHA256SUMS.txt)。

## 使用

进入世界按 G，或输入 `/carpetgui`。多人游戏客户端和服务端均需安装本模组与依赖。

详见 [使用说明.txt](使用说明.txt)。

## 源码与构建

完整源码以 [carpet-gui-1.0.4-source.zip](carpet-gui-1.0.4-source.zip) 发布，包含 Gradle Wrapper、构建配置、MIT 许可证与详细说明。下载并解压后，在项目根目录使用 JDK 25 构建：

```sh
# Windows
gradlew.bat build
# macOS / Linux
bash gradlew build
```

首次构建需要联网下载依赖。输出文件位于 `build/libs/`。更完整的功能、限制和历史验证记录请查看源码包内的 README。

## 许可证

保留项目原有 [MIT 许可证](LICENSE) 及版权声明。

## 本次发布

安装文件与用户提供的原始 JAR 一致。本次为整理发布，未重新进行游戏内测试。
