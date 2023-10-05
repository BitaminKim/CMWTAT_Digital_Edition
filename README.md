> Due to the closure of the Microsoft Digital License Issuance service, CMWTAT has temporarily disabled digital license activation. However, this does not affect the "Offline KMS" activation feature. There is no need to update CMWTAT; it should automatically switch to "Offline KMS" activation mode.
  
> 由于微软数字许可证下发服务关闭，CMWTAT 暂时关闭了数字许可证激活功能，但是这并不影响“离线 KMS”激活功能，无需更新 CMWTAT，它应该会自动切换到“离线 KMS”激活模式。  

# Official Site 官方网站

[https://cmwtat.cloudmoe.com]

# CloudMoe Windows 10+ Activation Toolkit Digital Edition

This toolkit can activate your Windows 10 and Windows 11 use digital license.

一款使用`CSharp`编写的 `Windows 10` 和 `Windows 11` 数字权利激活工具。

![UI界面截图][UI_image]

# Usage 使用

## Getting started 入门

### 使用自动模式激活 `Windows 10` 或 `Windows 11`

##### English Version

1. Download release `.exe` file.

2. Run it.

3. Click `Activate` button.

4. Enjoy it :)

##### 中文版

1. 下载 Releases 里的 `.exe` 发行文件。

2. 运行它。

3. 点按 `Activate` 按钮。

4. 完成~

## Advanced 进阶

### 在不同版本 `Windows` 之间转换

* 注意: 目前已知 `Windows` 的 `专业版（Professional）`、`专业工作站版（ProfessionalWorkstation）`、`教育版（Education）`、`专业教育版（ProfessionalEducation）`、`企业版（Enterprise）` 之间可以进行互相转换（N版本与LTSB版本除外），而这些版本与`家庭版（Core）`均不能直接一键转换，如需转换请使用 2.6 版本新增的 `升级到完整版 Windows` 功能或使用 `Windows设置` 中的 `更改产品密钥` 功能进行升级。  
激活 `物联网企业版（IoTEnterprise）` 版本前需要先激活 `企业版（Enterprise）`。

##### `Auto Mode` 自动模式

1. 运行它。

2. 选择 `Auto Mode` 。

3. 在下拉列表中选择要升级到的版本。

4. 点按 `Convert Versions` 按钮。

5. 完成。

##### `Manual Mode` 手动模式

1. 运行它。

2. 选择 `Manual Mode` 。

3. 输入框中输入需要升级到的版本对应的OEM零售密钥（不需要产品包装上的激活密钥，而是微软官方分配的密钥，如专业版对应密钥为 `VK7JG-NPHTM-C97JM-9MPGT-3V66T`）。

4. 点按 `Activate` 按钮。

5. 完成。

### 通过 `Manual Mode` 手动模式激活不在列表中的 `Windows` 版本

* 注意:  此方法不适用于某些版本的激活，如 `专业教育版（ProfessionalEducation）` ，即使你输入了对应的OEM零售密钥。

1. 运行它。

2. 选择 `Manual Mode` 。

3. 输入框中输入需要升级到的版本对应的OEM零售密钥（不需要产品包装上的激活密钥，而是微软官方分配的密钥，如专业版对应密钥为 `VK7JG-NPHTM-C97JM-9MPGT-3V66T`）。

4. 点按 `Convert Versions` 按钮。

5. 完成。

## Startup Parameters 启动参数

```
-?  --help            启动后弹出启动参数帮助对话框。
-a  --auto            启动后自动激活系统。
-e  --expact          自动激活系统时允许使用实验性方案。（需要与 -a 或 --auto 配合使用）
-h  --hide            以隐藏模式启动，激活进度以通知形式显示。（需要与 -a 或 --auto 配合使用）
```

# License 许可协议

[GPL-2.0](./LICENSE)

# Contributors 贡献者

[https://github.com/TGSAN/CMWTAT_Digital_Edition/graphs/contributors]

[UI_image]:./images/UI.jpg
[https://cmwtat.cloudmoe.com]:https://cmwtat.cloudmoe.com
[https://github.com/TGSAN/CMWTAT_Digital_Edition/graphs/contributors]:https://github.com/TGSAN/CMWTAT_Digital_Edition/graphs/contributors
