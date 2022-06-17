# pam-ssh-2fa

构建 PAM（pam_python）模块的环境登录黑盒
- 双因素认证-Demo搭建：2FA（Two-factor authentication）

- 使用场景：Centos7.x / python2.7

- 登录测试
```shell
[view@localhost ~]$ ssh admin@10.0.0.139
Warning: Permanently added '10.0.0.139' (ED25519) to the list of known hosts.
Authorized uses only. All activity may be monitored and reported.
(admin@10.0.0.139) Password: ******
(admin@10.0.0.139) Enter 2-factor auth: ****
Last login: Fri Jun 17 18:27:10 2022 from 10.0.0.100
Authorized uses only. All activity may be monitored and reported.
[admin@localhost ~]$ 
```
