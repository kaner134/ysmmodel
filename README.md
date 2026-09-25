YsmModel 源码整理包
====================

本目录从 openzen 提取 YsmModel、YSM 解析/动画/压缩依赖、渲染注入和内置模型资源。

源码入口：src/main/java/YsmModel.java
运行时源码：src/main/java/shit/zen/ysm/、src/main/java/com/elfmcys/、src/main/java/ysm/
渲染注入：src/main/java/LivingEntityRendererPatch.java、HumanoidModelPatch.java、YsmFirstPersonHandRenderer.java
资源：src/main/resources/ysm/

说明：这是当前工程的源码快照，不是独立 Gradle 工程。它依赖 Minecraft/Forge、Gson、Lombok 以及 OpenZen 的 ClientBase、事件和渲染工具。独立编译时需要补齐这些依赖和注入注册。内置模型包括 Alice、boqijiang、toyota_ae86、yatuoya。
