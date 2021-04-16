
# 《需求报告说明书》
## 一、 引言<br>
### 1.编写目的：
《软件需求规格说明书》主要是为四维口袋所撰写的需求规格说明书，系统包括用户上传下载功能和后台管理两部分。
本说明书在于清晰地指导最终用户、开发者完成对本云盘系统的目标，描述项目系统的功能结构和整体结构，通过本文档定义的需求，以求项目成员和用户可以达成一致的需求描述。同时此文档也是不断实践的方向和最后产品测试、成果验收的依据。
### 2.项目背景：
小程序名称：图书馆阅读打卡
开发者：福州大学至诚学院2018级课堂小组 
本项目经过了用户需求问卷调研，并深入分析用户需求以及现有产品痛点。图书馆是高校学生自习的主要场所，但由于学生无人监督，课外学习基本靠自主性，导致两极分化较严重，特此推出“图书馆阅读打卡”小程序，用来督促高校学生养成阅读学习的好习惯。形成良好的学习风气。
### 3.范围：
本期项目建设范围包括：定位打卡，打卡分享，打卡周报，打卡记录，打卡排行榜。
### 4.预期读者：
（1）项目经理：该职位成员可以根据此文档进行系统设计，项目管理
（2）程序员：根据该文档对云盘系统进行开发工作
（3）测试员：根据文档对该产品进行测试用例，进行功能性测试和非功能性测试
（4）用户：了解产品的功能
## 二、 项目logo
<img src="https://github.com/SoftWorkers/Demand/blob/photo/QQ%E5%9B%BE%E7%89%8720210415154454.png" width=100>

## 三、 业务描述
### 1、 用例图

<img src="https://github.com/SoftWorkers/Demand/blob/photo/%E7%94%A8%E4%BE%8B%E5%9B%BE.png" width=500>

### 2、 类图

<img src="https://github.com/SoftWorkers/Demand/blob/photo/%E7%B1%BB%E5%9B%BE.png" width=500>

### 3、 顺序图

<img src="https://github.com/SoftWorkers/Demand/blob/photo/%E9%A1%BA%E5%BA%8F%E5%9B%BE.png" width=500>

### 4、 活动图

<img src="https://github.com/SoftWorkers/Demand/blob/photo/%E6%B4%BB%E5%8A%A8.png" width=500>

### 5、 状态图

<img src="https://github.com/SoftWorkers/Demand/blob/photo/%E7%8A%B6%E6%80%81.png" width=500>

### 6、 泳道图

<img src="https://github.com/SoftWorkers/Demand/blob/photo/%E6%B3%B3%E9%81%93.png" width=500>

## 四、 用户场景
用户:A
性别：男
困难：自制力差，学习不主动不积极，一个学期最多期末考试前去几趟图书馆
典型场景：闲暇时间待在宿舍玩耍，不能自主学习，越来越懒，感受不到学习氛围。
用户定位：本产品可以很好地督促自主学习，阅读打卡，营造良好的学习氛围。

用户：B
性别：女
困难：常去图书馆，但是没有一个激励自己坚持阅读的理由，除了靠自己说服自己要多阅读才有可能更稳重，但总少了一些记录性、积累性的东西。
典型场景：一个学期阅读了很多本书籍，但是回头想想全都忘光了，没有纪念意义。
用户定位：本产品可以有阅读打卡排行榜和打卡年度报告，用户对自己一年的累积量一目了然。
## 五、界面原型
### 部分原型展示：
### 用户界面：

<img src="https://github.com/SoftWorkers/Demand/blob/photo/1_%E7%99%BB%E5%BD%95.png " width=500>

<img src="https://github.com/SoftWorkers/Demand/blob/photo/2_%E9%A6%96%E9%A1%B5.png " width=500>

<img src="https://github.com/SoftWorkers/Demand/blob/photo/2-1_%E6%89%93%E5%8D%A1.png " width=500>

<img src="https://github.com/SoftWorkers/Demand/blob/photo/2-4_%E6%89%93%E5%8D%A1%E6%8E%92%E8%A1%8C%E6%A6%9C.png  " width=500>

<img src="https://github.com/SoftWorkers/Demand/blob/photo/2-6_%E6%88%91%E7%9A%84%E8%B4%A6%E5%8F%B7.png " width=500>

### 管理员界面：

<img src="https://github.com/SoftWorkers/Demand/blob/photo/1_%E7%AE%A1%E7%90%86%E7%99%BB%E5%BD%95%E7%95%8C%E9%9D%A2.png" width=500>

<img src="https://github.com/SoftWorkers/Demand/blob/photo/3-1_%E5%AD%A6%E7%94%9F%E8%B4%A6%E6%88%B7%E7%AE%A1%E7%90%86_%E6%89%93%E5%8D%A1%E6%8F%90%E9%86%92.png " width=500>

<img src="https://github.com/SoftWorkers/Demand/blob/photo/3_%E5%AD%A6%E7%94%9F%E8%B4%A6%E6%88%B7%E7%AE%A1%E7%90%86.png " width=500>

<img src="https://github.com/SoftWorkers/Demand/blob/photo/4_%E5%AD%A6%E7%94%9F%E6%B6%88%E6%81%AF_%E5%B7%B2%E8%A7%A3%E5%86%B3.png " width=500>

## 六、功能描述
#### 注册登录：
注册：如果没有账号的话，可以通过手机号注册，注册完成后要与学号绑定，方便之后的打卡操作。
登录：可以通过学号和密码登录，也可以通过手机号和验证码登录。
#### 打卡提醒：
有提醒功能，在固定的时间段会在程序里面发送通知提醒打卡。
#### 定位打卡：
在打卡的时候程序会获取你的地址，如果位置在图书馆，打卡成功，如果检测到不在图书馆，则提醒因不在图书馆所以打卡失败。
#### 打卡周报：
会总结用户一周内打卡的次数，打卡的总天数，每天打卡的时长。
#### 打卡记录：
可以查看从打卡开始有哪几天打卡了，有效记录你打卡的过程。
#### 排行榜：
后台会统计所有学生打卡天数的排行，做出榜单。
## 七、验收验证标准
|测试功能|测试项|输入/操作|校验点|预测结果|验收情况|
|-------|------|---------|-----|-------|-------|
|小程序                            |
|登录界面|本地功能|输入账号文本框|账号为5-8字符|对于超过或没达到的字符进行预测识别，并提示|
|输入密码框|密码长度6-16位，可由数字、英文、下划线符任意组合|对于非法文本可以进行与现实别，并提示|  |  |   |
|点击"注册"按钮|注册功能|点击快速注册按钮，可进入相应界面||||
|点击"忘记密码"按钮|忘记密码功能|点击忘记密码按钮，可进入相应的界面||||
|登录功能|点击"登录"按钮|账号密码校验，并显示登陆结果信息|对于上述非法文本，以及账号密码不匹配的情况，返回登录失败信息|||
|注册界面|本地功能|点击注册手机号、密码、再次确认密码文本框||||
|输入注册手机号、密码、再次确认密码文本框|能够对注册手机号、密码、再次确认密码进行非法检测|若注册手机号、密码、再次确认密码非法，进行提示||||
|点击"其他方式登录>>微信登录|点击后能返回到微信登录界面|成功返回微信登陆界面||||
|注册功能|点击"注册"按钮|注册信息校验，并返回注册结果信息|进行注册手机号及密码，再次确认密码的检验，如果全部合法且符合要求，显示注册成功，否则显示注册失败|||
|打卡|点击"去打卡"的按钮|能否转至打卡的界面|成功转至打卡的界面|||
|我的账号|点击"我的账号"的按钮|能否转至我的账号界面|成功转至我的账号界面|||
|点击"打卡"按钮|能否打卡成功|成功打卡||||
|查看他人打卡情况界面|点击进入列表中的未打卡项且选择"通过"或"未通过"按钮|能否成功选择|成功选择|||
|联系客服|联系客服界面|点击“联系客服”按钮|能否查看相关内容|成功查看相关内容||
|打卡记录|打卡记录界面|点击“打卡记录”按钮|能否查看相关内容|成功查看相关内容||
|查看定位地|打卡定位地界面|点击“定位打卡”|查看定位处是否为图书馆|查看到所在地为图书馆||
|点击"<-"键|能否返回上一级|成功返回上一级||||
|排行榜|打开排行榜界面|点击排行榜|能否按打卡时列出打卡排名|成功查看打卡排名||
|连续打卡|打开“我的账号”||是否出现连续打卡天数|||
|打卡提醒|打开“打卡提醒”按钮|设置需要打卡的时间|能否在指定的时间进行打卡提醒|成功在指定时间进行打卡提醒||
|打卡周报|打开“打卡周报”界面|根据每位学生打卡的日期和时间进行统计|能查看到相关内容|||
|更新个人信息|点击“更新”|跳转到编辑个人资料"|编辑个人资料功能|进入编辑个人资料界面，修改用户名，修改头像||
|猜你想问|点击"猜你想问"|出现常见学生问的问题|查看问题解决方法|||
|点击"去反馈"|提交问题与建议|向人工客服发出问题与意见||||
|"返回"按钮|点击"<-"键|能否返回上一级|成功返回上一级|||
|后台管理||||||
|登录界面|本地功能|输入账号文本框|账号为5-8字符|对于超过或没达到的字符进行预测识别，并提示||
|输入密码框|密码长度6-16位，可由数字、英文、下划线符任意组合|对于非法文本可以进行与现实别，并提示||||
|忘记密码|点击“忘记密码”|通过手机号和验证码进行验证点击下一步重置密码|成功修改密码|||
|点击"新用户注册"按钮|注册功能|点击快速注册按钮，可进入相应界面||||
|手机快捷登录|点击“手机号快捷登录”|通过手机号和验证码进行登录|成功登录|||
|登录功能|点击"登录"按钮|账号密码校验，并显示登陆结果信息|对于上述非法文本，以及账号密码不匹配的情况，返回登录失败信息|||
|首页|打开首页界面|点击“首页”按钮|能否查看相关内容|成功查看相关内容||
|收集打卡记录|打开首页界面|点击首页中“打卡日志记录”按钮|能否查看相关内容|成功查看相关内容||
|学生账户管理|打开学生账户管理|点击“学生账户管理”按钮|能否查看相关内容|成功查看相关内容||
|打卡提醒|打开学生账户管理|点击“学生账户管理”中单个学生的打卡提醒|能否提醒个别学生打卡|成功提醒个别学生打卡||
|一键提醒打卡|打开学生账户管理|点击“一键提醒打卡按钮”|能否一键提醒学生打卡|成功一键提醒学生打卡||
|学生反馈|打开学生消息界面|查看学生反馈已解决的和未解决的|能否查看相关内容|成功查看相关内容||
|设置界面|点击“设置按钮”|能否跳转到设置界面|成功转至设置界面|||
|设置模块|管理员信息模块|其中包含管理员账号，外观，高级，关于悦读，系统，安全检查，隐私设置和安全性|能否进行查看和编辑|进入页面，进行查看和修改||
|切换账号|点击设置中的“切换账号“按钮”|能否跳转到切换账号页面|成功切换账号|||
|退出账号|点击"退出账号"按钮|能否退出账号|成功退出账号，回到登录界面|||
|"返回"按钮|点击"<-"键|能否返回上一级|成功返回上一级|||
|登录界面|本地功能|输入账号文本框|账号为5-8字符|对于超过或没达到的字符进行预测识别，并提示||
|输入密码框|密码长度6-16位，可由数字、英文、下划线符任意组合|对于非法文本可以进行与现实别，并提示||||
|点击"注册"按钮|注册功能|点击快速注册按钮，可进入相应界面||||
|点击"忘记密码"按钮|忘记密码功能|点击忘记密码按钮，可进入相应的界面||||
|登录功能|点击"登录"按钮|账号密码校验，并显示登陆结果信息|对于上述非法文本，以及账号密码不匹配的情况，返回登录失败信息|||
|注册界面|本地功能|点击注册手机号、密码、再次确认密码文本框||||
|点击同意《用户服务协议》前置方框|同意《用户服务协议》|方框可点击，一开始处于空白状态，点击后方框内出现钩，再次点击返回空白状态||||
|输入注册手机号、密码、再次确认密码文本框|能够对注册手机号、密码、再次确认密码进行非法检测|若注册手机号、密码、再次确认密码非法，进行提示||||
|点击"已有账户，立即登录"|点击后能返回登录界面|成功返回登陆界面||||
|注册功能|点击"注册"按钮|注册信息校验，并返回注册结果信息|进行注册手机号及密码，再次确认密码的检验，如果全部合法且符合要求，显示注册成功，否则显示注册失败|||
|打卡|点击"打卡"的按钮|能否转至打卡的界面|成功转至打卡的界面|||
|我的|点击"我的"的按钮|能否转至我的界面|成功转至我的界面|||
|点击"打卡"按钮|能否打卡成功|成功打卡||||
|查看他人打卡情况界面|点击进入列表中的未打卡项且选择"通过"或"未通过"按钮|能否成功选择|成功选择|||
|我的模块|打卡时长界面|点击“打卡时长”按钮|能否查看相关内容|成功查看相关内容||
|查看打卡次数|打卡次数界面|点击“打卡记录”按钮|能否查看相关内容|成功查看相关内容||
|查看定位地|打卡定位地界面|点击“定位打卡”|查看定位处是否为图书馆|查看到所在地为图书馆||
|点击"&lt;"键|能否返回上一级|成功返回上一级||||
|排行榜|打开排行榜界面|点击排行榜|能否按打卡时长列出打卡排名|成功查看打卡排名|||
|打卡提醒|打开“打卡提醒”按钮|设置需要打卡的时间|能否在指定的时间进行打卡提醒|成功在指定时间进行打卡提醒||
|打卡周报|打开“打卡周报”界面|根据每位学生的阅读书目生成喜爱类型，并统计时长|能查看到相关内容|||
|设置界面|点击右上角"设置"按钮|能否转至设置界面|成功转至设置界面|||
|设置模块|个人信息版块|点击"编辑个人资料"|编辑个人资料功能|进入编辑个人资料界面，修改用户名，修改头像|||
|系统通知、意见反馈、设置模块|点击"系统通知"|系统通知|查看系统通知|||
|点击"意见反馈"|意见反馈|提交建议||||
|退出账号"按钮|点击"退出账号"按钮|能否退出账号|成功退出账号，回到登录界面
|"返回"按钮|点击"&lt;"键|能否返回上一级|成功返回上一级|||




