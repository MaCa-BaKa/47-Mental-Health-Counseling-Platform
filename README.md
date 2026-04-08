# 47-心理健康咨询平台-Deepseek接入智能咨询

[文档地址](http://wechat.zjrcsy.cn/)

##### 技术栈:springBoot+Vue+Mysql+MyBatis+Deepseek接入智能咨询


##### 用户端: 

1.首页:展示心理咨询教育课程列表,可进行评价
2.在线预约：可根据医生排班进行咨询预约,可对医生的研究领域进行选择
3.心理测试：根据对应的试题进行测试,AI对测试结果进行智能分析
4.社区交流：查看交流列表,可选择感兴趣的进行交流互动
5.AI咨询：AI对话,实时咨询
6.我的测试：可查看自己的测试结果分析
7.我的预约：查看已预约信息



##### 心理医生端：

1.系统首页：展示平台测试问卷数、课程数、注册用户数、医生数、已测试人数，跟进测评待关注用户，Echarts图展示分析平台数据
2.课程管理:   编辑和新增课程并提交到管理员审核、查看用户的课程留言
3.心理测评管理:  新增题库、新增测评试卷、对用户的测评给出结果、查看异常数据
4.问诊记录：反馈问诊结果，查看问诊对话；查看预约记录，对预约进行反馈
5.排班管理：查看自己的排班
6.AI智能对话：Deepseek接入，智能咨询对话



##### 管理员端: 

1.系统首页：展示平台测试问卷数、课程数、注册用户数、医生数、已测试人数，跟进测评待关注用户，Echarts图展示分析平台数据
2.用户管理：查看用户，可进行操作，查看医生并审核医生的注册和操作
3.课程管理:   查看咨询课程列表，可对课程进行审核和操作，查看用户的课程留言
4.心理测评管理:  编辑操作题库、对测评试卷进行审核和查看及操作、查看用户测评记录、查看异常数据
5.问诊记录：查看用户和医生的问诊对话、查看预约记录
6.定时管理：设置用户定时测评任务并统计完成情况、查阅用户的测试进度
7.排班管理：对医生进行排班操作
7.AI智能对话：Deepseek接入，智能咨询对话



##### 用户端图:

![image-20260407220219445](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220219445.png)

![image-20260407220348370](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220348370.png)

![image-20260407220406981](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220406981.png)

![image-20260407220424459](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220424459.png)

![image-20260407220440129](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220440129.png)

![image-20260407220453382](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220453382.png)

![image-20260407220501148](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220501148.png)

![image-20260407220507257](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220507257.png)

![image-20260407220517380](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220517380.png)

![image-20260407220522929](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220522929.png)

![image-20260407220528932](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220528932.png)



##### 心理医生端图：

![image-20260407215912048](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407215912048.png)

![image-20260407220002201](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220002201.png)

![image-20260407220006660](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220006660.png)

![image-20260407220017529](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220017529.png)

![image-20260407220026384](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220026384.png)

![image-20260407220033463](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220033463.png)

![image-20260407220042605](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220042605.png)

![image-20260407220052707](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220052707.png)

![image-20260407220059991](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220059991.png)

![image-20260407220113016](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220113016.png)

![image-20260407220121137](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220121137.png)

![image-20260407220133738](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220133738.png)



##### 管理员端图:

![image-20260407220602210](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220602210.png)

![image-20260407215928188](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407215928188.png)

![image-20260407215942679](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407215942679.png)

![image-20260407220642674](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220642674.png)

![image-20260407220701364](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220701364.png)

![image-20260407220708092](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220708092.png)

![image-20260407220713446](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220713446.png)

![image-20260407220722664](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220722664.png)

![image-20260407220730143](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220730143.png)

![image-20260407220740664](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220740664.png)

![image-20260407220751870](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220751870.png)

![image-20260407220817830](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220817830.png)

![image-20260407220851036](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220851036.png)

![image-20260407220857125](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220857125.png)

![image-20260407220909027](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220909027.png)

![image-20260407220922886](https://yunzhuceshi.oss-cn-beijing.aliyuncs.com/typoraImg/image-20260407220922886.png)
