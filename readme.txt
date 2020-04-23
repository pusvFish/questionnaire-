# Questionnaire
PHP项目--问卷调查

前台：
index.php，首页，用于展示网站特点，可以登录，注册，以及可以通过立即使用跳转到use-method页，创建问卷。在用户登录过之后首页隐藏登录，注册，显示用户名

login，登录页
register，注册页

use-method创建问卷，可以选择现成的问卷，或者手动创建问卷
create 手动创建问卷
mould模板页，用于展示现成的问卷模板，导航栏用于展示问卷分类，用户点击相应的分类，下方展示相应的问卷

后台：
管理员：admin
普通用户：root
密码全是123456

使用php_studypro，2020年最新版
apache为2.4.39
MySql5.7.26
PhP版本5.4.45（重要5.4版本，高了，低了，得改很多地方）

修改：1）：gd_image.inc.php文件 $this->红色波浪线，修改为 self::(不一定出现，没问题忽略)
2)home/core/MySQLDB.php修改my_connection函数 $port, $user,$pass
最下面db数组进行相应修改，基本没什么问题了。

mysql utf-8