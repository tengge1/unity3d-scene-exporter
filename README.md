# Unity3DSceneExporter
导出Unity3D中的场景

使用方法：

1. 打开要导出的场景，点击菜单“File”/“Build Settings...”，点击“Add Open Scenes”添加本场景。

2. 在Unity3D的Project面板新建Editor文件夹，添加本项目Editor中的两个cs文件。

3. 下载LitJson.dll，放到Unity3D项目Assets文件夹下。

4. 在Assets目录下新建StreamingAssets文件夹。

5. 按F5刷新菜单，点击“GameObject”菜单下的“ExportXML”或“ExportJSON”菜单即可将场景导出为xml或json文件，导出的文件在Assets/StreamingAssets文件夹。
