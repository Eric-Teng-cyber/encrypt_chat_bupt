# encrypt_chat_bupt
安全即时通信软件

题目1:支持安全认证、加密传输和加密存储的安全即时通信软件

支持口令和可信任信息授权认证机制，实现即时通信软件的认证登录;支持多人之间的文字、语音和文件等消息和文件信息的双向即时和离线消息安全传输;支持消息和文件信息的端到端加密传输和本地加密存储，支持一次- ~密 加密传输机制，支持防篡改和防中间人攻击。只有加密存储的最初用户可以解密磁盘空间的加密数据，支持安全的加密数据找回机制。支持消息和文件信息在用户中的同步销毁。支持对特定消息的阅后即焚功能，特定消息不可被复试、剪切、转发、保存。


注:不能使用开源软件实现，不能直接调用SSL、TLS或IPSec的开源软件和函数实现。


测试环境:
在3台计算机、手机中安装此系统，在3用户之间进行注册、登录、多用户加密传输等_上述本题目要求的功能，实现数据信息的安全传输验证。



提示:
网络socket编程技术;
密码算法和加解密API编程技术;
对称加密算法和非对称加密算法的应用。
