# Triple C Tech Lead 工作内容介绍

## 职责概述：
- 作为Tech Lead，你是在项目组的技术层面上最有发言权和决定权的人。你需要在技术方面指导组内的其他developers，并引领团队完成技术攻坚。为此，你需要比组内的任何一个developer都花费更多的时间和经历，但收获到的东西也会更多。

## 职责详述：
1. 确定项目组使用的技术栈/框架
    - 与PM/PD/其他developers协商，按项目需求确定
    - 建议优先选择你自己熟悉的/使用过的框架（避免与developers跨服交流*）
    - 如果选择了自己未使用过/不熟悉的框架，最好在正式开发开始之前花时间去学一下

2. 培训组员
    - 如果有组员没有使用过将要用到的包/工具/框架，那么tech lead需要对他/她进行培训
    - 不一定要亲自开lecture或者workshop，直接发一些网上的教程也可以

3. 联系Tech Chair 创建项目组的 Repository

4. 邀请项目组的所有developers加入新建的 Repository

5. 和 PM 一起确定项目的技术需求
    - 确定需求的优先程度
    - 确定哪些需求技术上难以实现，应该暂时搁置或放弃
    - 最好把新的需求拆分成不同任务(cards)，任务之间最好 mutually exclusive

6. 分配developers的工作任务
    - 根据这个迭代的所有新需求，把不同任务分配给合适的 dev
    - 可以开会的时候讲工作任务，可以写到某个doc里然后share给组员，也可以微信发给组员
    - 需要确保组员完全明白这个工作周期要做哪些事

7. 代码审核
    - 在有时间的前提下做
    - 检查组员提交的代码有无明显的问题，有的话及时通知组员进行修改

8. 解决merge conflict
    - 开发时可以每一个developer开一个新的branch完成任务；每个branch上修改的文件尽量不要交叉，任务完成之后再把 branc h给 merge 到 master / dev branch上
    - 也可以大家都在 master / dev branch上开发，获取代码时用 `git pull --rebase`，每个 dev 自行解决 conflict

9. 当然，tech lead也是developers之一，所以也是要写码的

## 脚注
[跨服交流](https://zh.moegirl.org.cn/index.php?title=%E8%B7%A8%E6%9C%8D%E8%81%8A%E5%A4%A9&variant=zh-hans&mobileaction=toggle_view_desktop)：指交谈双方，不在同一语境下进行交流  
