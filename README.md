# PassWordManager
密码加密记录备份管理工具

## 使用
1. 打开/创建 按钮: 存在的文件则打开，不存在的则创建
2. 确认文件密码: 文件存在密码则确认密码，否则（新创建的文件）为设置密码
3. 修改按钮: 文件成功打开后方可修改文件密码
4. 在下方添加区添加项，其中关键字、备注支持中文但不支持中文字符
5. 查询点击下拉展示关键字，输入则匹配关键字、用户名、密码进行查询
6. 点击表头 关键字、用户名、备注可对查询结果进行排序显示

## 日志：
1.1 正式版
1.  增强查询
2.  增加可翻页
3.  增加可排序
1.0 正式版
1. 修复：超长限制，关键字、用户名、密码、备注等均不允许超过60字
2. 增加：密码文件备份管理，若有修改则退出程序或打开别的文件前备份修改前的文件，备份保留最新9个
