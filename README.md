## 框架

### 前端

### 后端



### Login

1. login界面

2. cookie保存login info

3. Class User

4. GET /yemaoniu/login; /yemaoniu/

   ```json
   {
     ID:(P)
     Email:(P)
     Nickname:
     Password:
     
     Age:
     University:
     Zipcode:
     First Name(Option):
     Middle Name(Option):
     Last Name(Option):
     
     OpenAccountTime:
     
   }
   ```

#### 业务逻辑

1. localhost/
   1. 检查cookie，跳转/login
2. ~/login 界面有signup
3. ~/signup 
   1. 输入上述信息，POST
   2. 跳转login
4. 数据库加密保存用户密码