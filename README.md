这是个基于php symfony 的在线考试系统
第一个版本具备如下的功能：
管理员功能：
用户分为注册用户和内部用户；
注册用户是通过注册页面注册的用户；
内部用户是管理员通过后台管理增加的用户，或者是通过数据导入生成的用户；
管理员可以激活、禁止用户，新导入的用户或者新注册的用户默认是激活状态；
被禁止的用户不能做题，但是可以登陆系统查看已经做过的试题；
管理员可以查看用户录入的试题；
管理员可以根据科目类别查看注册用户的考试情况；
管理员可以查看某个用户的各个科目的考试情况；
管理员可以添加试题类别；
管理员可以根据类别添加试卷，并设置试卷游客可以看到的题目数量；

注册用户功能：
在线选择类别录入试题的类别；
如果没有要录入的类别可以自己创建；
注册用户可以录入单选题、多选题、主观题；
注册用户录入完之后，角色就从普通用户转变为试题管理员角色；
试题管理员可以查看录入试卷的完成人数、每个人的考试成绩；
试题管理员可以设置试卷的考试时长；
试题管理员可以设置试卷的考试有限期；
普通用户可以在线浏览试卷，可以根据考试科目浏览试卷、根据试卷名称浏览、根据发布试卷人的用户昵称搜索；

游客角色功能：
普通游客能够注册用户；
能够浏览每个科目的试卷前10个题目，如果查看更多，提示游客需要登陆或者注册；
游客可以查看每个试卷用户完成的人数，以及每个试卷用户完成的成绩分布情况；
