# chatapp 
### 二级项目-软件基础设计-聊天软件 
C++(Qt) 实现

### 环境配置
Qt Creator 5.9.0 + MSVC2015_32bit

### 说明
#### 源码文件夹
chatboard_v1, server_v1  
已在代码文件中添加详细注释

#### 可执行程序文件
client/chatboard_v1.exe (客户端)  
server/server_v1.exe (服务端)  
*问题不大的话在一台机子运行测试应该是可以的，即使实现效果很差*

#### 测试方法
虽然做得很烂，但是可以参考对比一下下
* 1. 运行server_v1.exe，点击startService按钮
* 2. 打开两个客户端(chatboard_v1.exe)，分别用账号`user1`, `user2`和密码`123`登陆
* 3. 客户端选中聊天对象（如user1用户选中好友列表中的user2）
* 4. 发送消息
