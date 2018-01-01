# TestSingleTask
测试 Android 的 singleTask 启动模式的示例

该示例是为了验证 「Android 开发艺术探索」一书中的 20 页最上方提出的现象的真实性。

现象内容不做过多描述，请读者查阅书籍即可。

## 示例内容说明
本项目中有两个 module，一个是 app module，另一个是 otherapp module。

为验证书中提及的现象，请安装这两个应用，并打开名为：TestSingleTask 的应用。
 
TestSingleTask 的应用中的按钮功能为启动 otherapp 应用中的 Main2Activity（隐式意图）

待开启 otherapp 应用中的 Main2Activity 后，点击 Home 键，然后点击 otherapp，即可验证书中提到的结果。