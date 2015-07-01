# frontend
## 创建用户
#url  v1/user/create

#email注册
1)type =1
2)user_email
3)user_pwd  md5后传过来

```javascript
{
success: 1
data: {
user_sex: "S"
user_token_id: "1364"
user_email: "abdddc@dddfadf.com"
user_pwd: "134d2faab6219d698ea5d30ab75602a8"
nick_name: "abdddc"
user_ext: "1"
user_id: "1366"
user_ext_id: null
user_ext_name: null
user_ico_n: null
user_ico_b: null
user_ico_s: null
user_back_img: null
user_token: "d7bba7e09228f3e17616fa27677e0aeeb9740e92"
token_start: 1435743147
token_end: 1435746747
}-
message: ""
}

```
#第三方用户注册
1）user_ext_id
2）user_ico 用户头象
3)nick_name 用户昵称
4)unique_str 第三方平台唯一标识

成功时返回
```javascript
{
success: 1
data: {
user_sex: "S"
user_token_id: 0
nick_name: "adfddd"
unique_str: "ffddss222"
user_ext: "2"
user_ext_name: "face_book"
user_ico_b: "xxxxx.jpg"
access_token: "12f92047590eff25db400a459164ec19"
user_id: "1369"
user_pwd: null
user_email: null
user_ico_n: null
user_ico_s: null
user_back_img: null
}-
message: ""
}
```
