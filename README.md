https://github.com/Wisdom-Lord/Internet_interface_assistant
<img width="1600" height="932" alt="651b7958-44de-4e6c-a0e2-29eeddc664f9-20251125175142-bcz4qf9" src="https://github.com/user-attachments/assets/9b84ce6a-cac4-4972-9205-1c7499bd99b6" />

2. 设置帧名称、帧头、分隔符、帧尾等基本信息

<img width="1604" height="933" alt="image-20251125175415-1roayml" src="https://github.com/user-attachments/assets/e83fa024-8fc0-4b0b-9530-e0b1c53f97fc" />


<img width="451" height="388" alt="image-20251125175517-pxb9xyd" src="https://github.com/user-attachments/assets/7f2e399e-1679-4d0b-8ae0-3bed791708c5" />


<img width="1601" height="932" alt="image-20251125175629-te87h0g" src="https://github.com/user-attachments/assets/5a8a53f1-c5c6-45e4-8323-9af9c36fcfd2" />


1. 点击"保存帧基本信息"保存设置

#### 添加字段

1. 在"协议内容"区域点击"添加字段"
2. 设置字段索引、名称、类型、长度、描述等信息
3. 设置最小值和最大值（可选）
4. 点击"确定"添加字段
5. 协议配置页面的帧基本信息的帧头帧尾仅用于判断，解析时需另设置帧头帧尾的内容。

#### 保存与加载

1. 点击"保存配置"按钮保存协议配置
2. 点击"加载配置"按钮加载已保存的协议配置

### 4. 数据解析

1. 在"数据解析"标签页选择要使用的解析协议
2. 选择是否使用HEX解析模式
3. 接收到的数据将自动按协议解析并显示在表格中
4. 可点击"重新解析"按钮重新解析最后一条数据

## 配置文件

### 协议配置

- 协议配置文件保存在date目录下，文件名格式为JK_xxx.json
- 可通过"帧协议配置"标签页的"保存配置"和"加载配置"按钮管理

### 多字符串配置

- 多字符串配置保存在date/JK_multi_strings.json
- 可通过多字符串发送面板的"保存多字符串配置"和"加载多字符串配置"按钮管理

### 应用配置

- 应用配置自动保存在date/app_config.json
- 包含IP、端口、串口设置和多字符串数据等信息

## 打赏支持

如果您觉得本软件对您的工作有帮助，欢迎通过以下方式打赏支持开发者：

- **微信支付**：扫描微信收款码
- ![wechat_qrcode](https://github.com/user-attachments/assets/2497cca7-7379-4163-96ac-afe1a60b77ec)

- **支付宝**：扫描支付宝收款码
- ![alipay_qrcode](https://github.com/user-attachments/assets/23b2525a-a799-422e-a390-3f394c3ba0e4)


## 常见问题

### Q: 如何设置自定义协议？

A: 在"帧协议配置"标签页创建新协议，设置帧格式和字段信息，保存后即可在"数据解析"标签页使用。

### Q: 如何保存多组发送数据？

A: 使用多字符串发送功能，点击"保存多字符串配置"按钮保存当前设置，下次可通过"加载多字符串配置"恢复。

### Q: 如何查看历史通信数据？

A: 通信数据实时显示在"收发数据记录"区域，可复制保存，目前不支持自动保存历史记录。

### Q: 串口无法打开怎么办？

A: 检查串口是否被其他程序占用，确认串口参数设置正确，尝试重新插拔设备。

## 联系方式

如有任何问题或建议，请联系开发者。

## 更新日志

### v1.0.0

- 初始版本，支持UDP、TCP和串口通信
- 支持自定义协议解析
- 支持多字符串发送和定时发送功能
