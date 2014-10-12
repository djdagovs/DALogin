DALogin
=======

DALogin是一个由CCS登录页面更改而成的DirectAdmin专用的登录页面文件

你需要使用Putty软件并以root身份进入你的Directadmin服务器，编辑Directadmin的登录页面文件。

登录页面位置：<code>/usr/local/directadmin/data/templates/login.html</code>

保存后，你需要重启你的Directadmin,就可以生效了。

<code>service directadmin restart</code>

**注意**：login.html文件中的部分链接和文字你应该更改为你的。
