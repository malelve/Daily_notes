![](C:\Users\wps\Desktop\test_cba\image\image-20230307151541231.png)

![](C:\Users\wps\Desktop\test_cba\image\image-20230307151559403.png)

![](C:\Users\wps\Desktop\test_cba\image\image-20230307151608062.png)



![](C:\Users\wps\Desktop\test_cba\image\image-20230307155042556.png)

https://www.sohu.com/a/350735657_100192994





数据库设计

- 图书✔
  - Id
  - 书本Id
  - 作者
  - 书名
  - 类型
  - 所在馆
  - 索书号
  - 出版社
  - 状态：外借，空闲
- 位置✔
  - Id
  - 书本Id
  - 所在馆
  - 所在楼栋
  - 所在楼层
  - 所在书架
  - 坐标
- 用户✔
  - Id
  - 用户Id
  - 用户名
  - 密码
  - 电话号码
  - 学号
  - 学院
- 管理员✔
  - Id
  - 账号
  - 密码
  - 持有人
- 借阅
  - Id
  - 用户Id
  - 书本Id
  - 借阅日期
  - 归还日期
- 历史记录✔
  - Id
  - 用户Id
  - 用户名
  - 图书Id
  - 图书名称
  - 借阅日期
  - 归还日期
  - 状态：已结束，在进行，违规
- 公告表✔
  - Id
  - 标题
  - 内容
  - 图片
  - 发布日期
- 图书类型
  - 图书分类Id
  - 图书分类名称


https://cloud.tencent.com/developer/article/1697988

https://gitee.com/mingyuefusu/tushuguanlixitong#%E7%B3%BB%E7%BB%9F%E7%AE%A1%E7%90%86%E5%91%98

思考：

如何融入定位技术？

用户点击“前往书籍”后，界面跳转到类似腾讯地图界面，标出目的地，随着用户移动，画面刷新，用户可判断位置与距离。

ER图：

![](C:\Users\wps\Desktop\test_cba\image\image-20230307165703131.png)







![image-20230309092915971](.\image\image-20230309092915971.png)
