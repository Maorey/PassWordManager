# PassWordManager
密码加密记录备份管理工具

## 使用
1. **打开/创建** 按钮: 存在的文件则打开，不存在的则创建
2. **确认**文件密码: 文件存在密码则**确认**密码，否则（新创建的文件）为设置密码（**应用**）
3. **修改**按钮: 文件成功打开后方可修改文件密码
4. 在下方**添加**区添加项，其中**关键字**、**备注**支持中文但**不支持中文标点符号**
5. **查询**点击下拉展示关键字列表;输入则匹配**关键字**、**用户名**或**备注**
6. 查询结果区支持**双击**弹出编辑框编辑文本
7. 点击表头 **关键字**、**用户名**、**备注** 可对查询结果进行排序显示
8. 点击导出按钮（**->**）将当前查询结果导出、合并到另一密码文件，可用移除按钮移除不想导出的，移除不修改密码文件，可用**刷新**（或查询）重新显示

### 快捷键说明：

1. 最小化：Esc 或 Ctrl+M
2. 退出：Alt+F4
3. 打开/创建文件：F1 或 Ctrl+O
4. 导出/合并结果：F2 或 Ctrl+E
5. 搜索：F3 或 Ctrl+F
6. 查询：F4 或 Enter
7. 刷新：F5 或 Ctrl+R
8. 添加项：小键盘+号键 或 Alt + A
9. 上一页：←（Window获得焦点时） 或 Alt+←
10.下一页：→（Window获得焦点时） 或 Alt+→
11.首页：Home 或 Alt+↑
12.尾页：End 或 Alt+↓

## 日志：
### v1.2_2
1. 新增快捷键详见说明或程序标题提示
2. 细节处理
### v1.2
1. 将双击输入框复制文本改为双击弹出编辑框显示、编辑文本
2. 搜索*不再崩溃（正则改为字符串定位）
3. 细节处理
### v1.2 beta
1. 增加导出按钮（**->**），可将当前显示项全部导出、合并到另一密码文件
2. 增加移除按钮（**移**），可移除某项（不修改文件），可用**刷新**（或查询）重新显示
3. 修复排序状态修改项等时无效的问题等
### v1.1_3
1. 修复了排序后点击翻页不显示表示升序或降序的箭头及相应鼠标提示的问题
2. 查询时忽略大小写
3. 确认密码按钮根据确认密码还是修改或创建密码显示确认或应用
### v1.1
1.  增强查询
2.  增加可翻页
3.  增加可排序
4. 按钮颜色调整
### v1.0
1. 修复：超长限制，关键字、用户名、密码、备注等均不允许超过60字
2. 增加：密码文件备份管理，若有修改则退出程序或打开别的文件前备份修改前的文件，备份保留最新9个
