# 爬取Bilibili用户信息

* 文件说明：
  * Bilibili_users_info.py 爬取程序的主文件
  * proxies_test.py        代理ip有效性的测试文件
  * user_agents.txt        汇集了大量的U-A可以在以后的爬虫中运用
  * test_1.py              是一个开始爬取数据的测试文件，因为本来想等一个代理ip爬取失效后再更换代理（可以节省代理资源），但是发现Python运行中无故停止没有报错

如果有大神知道为什么爬虫在运行过程中暂停，但是没有报错请和我说一下，谢谢O(∩_∩)O

* 技能点：
  * 更换U-A；
  * 构造代理IP；
  * 数据写入PostgreSQL；
  * 尝试使用多进程进行爬取（不过发现速度提升的并不明显）

爬虫中踩到的坑已经在程序文件中进行了详细的说明

