# Team 10 - 6th Meeting （中文版）


## Information

**Time:** 2020.10.20 20:00~22:00

**Location:** Library 4F Project Room 30, 32

**Chairperson:** Ruizi Han

**Secretary:** Yiming Tang

**Translator:** 

**Attendence:** 6/6

| **出席** | **Yiming Tang, Shiliang Chen, <br>Yani Huang, Ruizi Han, <br>Yijie Lu, Yuting Jiang** |
| -------- | ------------------------------------------------------------ |
| 迟到     | 0                                                            |
| 缺席     | 0                                                            |



<br>

------

## Agenda

*全会预计120分钟*

1. 回顾上周的任务（预计3分钟）

	- 给heshan发邮件是否完成
	- heshan的资料分享
2. 需求分析（预计40分钟）

	- 大家分享各自想到的需求，某些部分可以顺带讲一讲怎么去measure这个需求
	- 确定我们产品的目标人群和市场分析（可以用在哪里，大家会多多用吗，竞品比对、分析，优点和限制，这部分heshan要求写在report里）
	- 讨论需求分析阶段我们要做的事（survey和interview来收集信息，确定functional和non-functional，画UML等）
	- 整合大家认可的需求，先有一个大致的需求分析文件
3. 选定SE method，讨论后面阶段的安排，初步确定流程（预计15分钟）

    - 那种SE method更适合我们？（或许像dave说的两者结合尝试一段时间）
    - 选定之后，讨论我们后面的计划，大致确定下之后要做的事情
4. ethics form（预计10分钟）
    - 简单介绍填写流程和几个文件
    - 分配任务
5. website（预计15分钟）
    - 黄雅妮和唐懿明同学讲一下自己的大致构想
    - 讨论并提出意见
6. 讨论correctness的定义（预计15分钟）
    - 关于correctness，大家提出自己的看法
    - 如何实现这一要求，可能的办法
7. 了解大家的性格和分享自己认为的组内角色 - 如果大家愿意分享的话（预计10分钟）
    - 分享测试结果或自己认为自己合适的Belbin team role
    - 之后的一年自己可能可以做些什么
8. 问题提出和下次任务安排（预计10分钟）

    - 提问，大家是否还有其他问题

    - 下次会议chairperson和secretary，以及之后的轮换方式

    - 下次会议时间

    - 确认要完成的事项，大家下阶段的任务

<br>

------


## Minute

（这部分归 Sec 写）

### Outcomes

（根据上面的Agenda来分点写，是否完成，结果如何。不要每句话都记，要记会议进程里讨论出的最终内容，summary of all discussed main points, all decisions, all action points）

1. 回顾上周的任务

	- 给heshan发邮件，已完成
	- heshan的资料，已经发到GitHub上
	
2. 需求分析（预计40分钟）

   - 大家分享各自想到的需求，某些部分可以顺带讲一讲怎么去measure这个需求

     1. tym：激励？

     2. jyt：闯关，游戏。先开放简单的给他，比如先冒泡，再开放其他的给他。但是这样的话假设他想学的在后面；积分。10分-》冒泡，积分，解锁（充值）；代币，升级，奖励机制；单个算法之内还是所有算法？里程碑；

     3. yn：两种模式，算法区分难度，奖励代币可以兑换什么，皮肤、界面颜色？

     4. rz：可能不会有长期用户，学完就丢了；所以我不想有登录，目标用户：自学编程、没理解的人

     	5. yn：efficiency，但是我们更注重correctness。让他自主地去完成在评价，还是在他完成时评价？
      	6. Csl：
           	1. 预制动画
           	2. 新手教程
                	1. 测试演示模块，让用户自己输入数字也可以，上一步、下一步、自动播放，让用户知道算法在干嘛
                	2. 用户拖动模块，（到时候再讨论有几个）因为他大概在理解，他自己模拟算法拖动的样子，比较有交互性，user-friendly，实时检测他是否拖对，比右边拖那个更有交互性，还可以提示
                	3. 解锁最终模块：scratch伪代码，可能有几个步骤是错的，让他纠错
                	4. 如果用户想看代码的话，给他看我们提供的各种语言的代码
      	7. 给他显示代码的时候，显示他想要的语言？heshan不是甲方，百分之多少的用户想看code，拿调查出来的东西给heshan确认。
      	8. 要帮他用户理解，掌握排序算法的意义吗？
      	9. 再问一次，correctness到底是什么，如何证明，我们没办法理解。

   - 确定我们产品的目标人群和市场分析（可以用在哪里，大家会多多用吗，竞品比对、分析，优点和限制，这部分heshan要求写在report里）

     - 不考虑小孩子，因为很难对付。
     - 对计算机有兴趣但基础的大学生。
     - 主人群：大一CS专业、教师

     市场分析

     - 发问卷、要不要ethic？

     竞品

     - literature review
     - 动画演示 https://www.cs.usfca.edu/~galles/visualization/ComparisonSort.html  ，不展示代码，只有动画排序
     2. 代码拼图 http://snapapps.github.io/edgy/app/edgy.html，看起来像拼伪代码，但是不是针对排序算法
     3. Galant图演示 https://github.com/mfms-ncsu/galant，库，虽然bar的形式做可能会单调，他们用的是galant图，也许可以代替这个东西
     4. Sortko：使用移动设备学习排序算法   https://ieeexplore.ieee.org/document/6185079，论文，是一个手机上的软件，这篇文章参考价值比较高，有收集资料。
     5. ViSA: Visualization of sorting algorithms 可视化   https://ieeexplore.ieee.org/document/6240816，论文，排序算法可视化，
     5. 这些都可以在 literature review里用到。教授的话，可以展示给他看。
     5. 算法动画图解

   - 讨论需求分析阶段我们要做的事（survey和interview来收集信息，确定functional和non-functional，画UML等）

     - 这次时间好像没来得及，没讨论这个事情？

   - 整合大家认可的需求，先有一个大致的需求分析文件

     - 

3. 选定SE method，讨论后面阶段的安排，初步确定流程（预计15分钟）

   - 那种SE method更适合我们？（或许像dave说的两者结合尝试一段时间）
     - Agile，边做过程可能边会有确认工作，有stackholder参与的过程。随意？
     - 大致的方向要说明白。
     - 测试文本化？测试文档化？确认了完整的功能之后，要非常明确的如何测试的过程和效果。
   - 选定之后，讨论我们后面的计划，大致确定下之后要做的事情
     - requirement，29？

4. ethics form（预计10分钟）

   - 简单介绍填写流程和几个文件
     - 填表、supervisor看、很长的表、
   - 分配任务，

5. website（预计15分钟）

   - 买了几个模版，挑到了一个模版，给大家看。只有一个index.html，以方便。
   - project brief（timeline之类的）、project document（下载链接、数据、代码version）、现阶段在做什么（周期、文件、介绍，持续更新）、Team成员介绍（email、分工）、其他的模块看还有什么别的需求
   - document怎么加在网站上。目前讨论的结果是放链接。这个事情tym来做。
   - 加项目介绍，文案要发。
   - logo

6. 讨论correctness的定义（预计15分钟）

   - 关于correctness，大家提出自己的看法
     - 符合定义？可以有自己的方式证明，in their way。
     - 告诉用户这个算法是正确的。
     - 
   - 如何实现这一要求，可能的办法

7. 了解大家的性格和分享自己认为的组内角色（预计10分钟）

   - 分享测试结果或自己认为自己合适的Belbin team role
     - 还没搞，再说吧
   - 之后的一年自己可能可以做些什么

8. 问题提出和下次任务安排（预计10分钟）

9. 下次会议准备 (实际完成时间: x分钟)
  - **Chairperson:** Colin 
  - **Secretary:** tym hyn
  - （再下一次 hyn + jyt）
  - **Time:** 周四 
  - (下次会议简略内容)跟进

问 agenda我们刚发给她的合不合适

latex排版的必要性

correction

requiments

ethic(form 我们什么时候可以survey)



<br>

-------


### Last stage's action points review

| **任务** | **负责人** | **报告** | **问题** | **完成度** |
| -------- | --------- | -------- | -------- | ---------- |
| Determine which SE process to use | 所有人 | / | 暂定 | 50% |
|          |            |          |          |            |
|          |            |          |          |            |

<br>


### Action points 

| **任务**                    | **负责人** | **DDL** |
| --------------------------- | ---------- | ------- |
| 问卷联系老师                | huangyani  | 10.29？ |
| 设计问卷，每个人想4-6个问题 | huangyani  | 10.21   |
| requirements确认            |            |         |
| ethics forms                | han、jiang |         |

<br>

### Problems

| **优先级（0最高，5最低）** | **问题描述**                                      | **预计后果** | **提出人** | **暂定解决方案** | **预计解决日期** |
| -------------------------- | ------------------------------------------------- | ------------ | ---------- | ---------------- | ---------------- |
| 3                          | agenda?会议记录放到report里是不是用word写比较好？ |              |            |                  |                  |
| 0                          | correctness到底什么定义，我们还是理解不了。       |              |            |                  |                  |
| 1                          | 跨平台？html？网页不算软件。用别的我觉得不行。    |              |            |                  |                  |

<br>

-------


## Comments

（这部分归 Leader 写，内容：这次会议进展的是否如预期？会议本身是否有问题？如何解决？）



（来自sec：我其实个人感觉对上次会议的总结不够全）