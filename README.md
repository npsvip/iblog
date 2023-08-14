# iblog
小白也可快速搭建的知识付费博客、社区，支持多主题，自适应，docker一键部署，会员和积分充值，已完成个人支付平台对接

# 前端
## 多主题
![1](https://github.com/npsvip/iblog/assets/95081538/3a3431bf-9608-48d0-9324-489b136dfb01)

![2](https://github.com/npsvip/iblog/assets/95081538/a938b6a8-bec0-46cc-990d-d6071eae08b1)

![3](https://github.com/npsvip/iblog/assets/95081538/436e4582-7be1-40a2-8db7-b78fb84b56d8)

![6](https://github.com/npsvip/iblog/assets/95081538/b041d092-6378-4153-8424-5712e78b7ab4)

## 自适应

![4](https://github.com/npsvip/iblog/assets/95081538/bf55b368-bc72-4320-8c1a-d9b5534ecc18)

![5](https://github.com/npsvip/iblog/assets/95081538/79616af1-9f32-4aee-8bca-e018ce7fbfac)

## 个人页

![7](https://github.com/npsvip/iblog/assets/95081538/6e7b374d-702d-4b31-91c3-56fff3dc3eee)

![8](https://github.com/npsvip/iblog/assets/95081538/7757976e-f581-4bf3-ba28-558bd293c0e6)

![9](https://github.com/npsvip/iblog/assets/95081538/c094258f-768b-4812-bfac-ef761eae731f)


# 后端
![10](https://github.com/npsvip/iblog/assets/95081538/58d96393-4c13-4c00-b4b8-3d49b2f17e12)

![11](https://github.com/npsvip/iblog/assets/95081538/77420d96-5902-44f1-848b-be0b1fe56bd2)

![12](https://github.com/npsvip/iblog/assets/95081538/66d44534-3bd3-4376-ae33-902bfb40ae60)

# H2 console

<img width="459" alt="image" src="https://github.com/npsvip/Hmart/assets/95081538/edfa4968-4dd9-48a2-9232-eafe74971caf">


<img width="1675" alt="image" src="https://github.com/npsvip/Hmart/assets/95081538/a8decf29-f09c-4285-ac13-a16174ea316f">


# 运行命令
```
docker run -d --name mall --restart=always -p 8080:8080 -e console=true -v /opt/logs/mall/:/opt/logs/mall/ aeert/mall:latest

# arm请使用 aeert/mall:arm 或 aeert/mall:arm64 镜像

```
日志目录&nbsp;&nbsp;&nbsp;&nbsp;/opt/logs/mall/<br/>
H2 console&nbsp;&nbsp;&nbsp;true 打开<br/>
H2数据库&nbsp;&nbsp;&nbsp;&nbsp;/mall.mv.db <br/>
上传文件&nbsp;&nbsp;&nbsp;&nbsp;/opt/file/

# 访问信息
体验地址&nbsp;&nbsp;&nbsp;&nbsp;https://mall.zwapi.cn<br/>
前端地址&nbsp;&nbsp;&nbsp;&nbsp;http://localhost:8080<br/>
后端地址&nbsp;&nbsp;&nbsp;&nbsp;http://localhost:8080/admin/<br/>
后端账户密码&nbsp;&nbsp;随意输入，之后会保存H2数据库<br/>
H2 console地址&nbsp;&nbsp;&nbsp;&nbsp;http://localhost:8080/h2<br/>
H2 console&nbsp;&nbsp;JDBC URL: jdbc:h2:./mall

# 支付平台
目前对接的是&nbsp;&nbsp;<a href="https://pay.npsvip.cn" target="_blank">蓝鲸支付</a>

# 相关推荐
<a href="https://github.com/npsvip/begger" target="_blank">Begger乞讨网</a>

# 版权信息
Hmart遵循 MIT License 协议，提供免费使用，请勿用于商业及非法用途,Hmart不承担个人行为的任何违法责任。
