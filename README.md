# pillars_of_eternity_Chinese
Pillars of Eternity Chinese translation pack | 永恒之柱中文汉化包

## 20160211 更新
> *官方的excel 文本就是一个坑。*
> 因为程序版本不停更新，文本也在不停变化，有删有减
> 使用官方 excel 之后，出来大量的 missing xxx
> 痛定思痛，考虑更换侧率
> * 使用当前程序内自带的 stringtable
> * 有翻译内容的，翻译结果
> * 没有翻译内容的，保留原始英文
> 手动测试了下，missing character 搞定了。 方向应该没问题

## 背景
* 永恒之柱3.0beta开始，官方提供了本地化工具包
* 但是现在无论是游侠还是 3DM 提供的汉化包，都无法兼容最新的版本
* 最无法忍受的地方是随处出现的「Missing xxx GUI」
       -> 残念。合并完之后，还是有大量的 miss gui。不知道是不是因为程序是3.0beta，翻译文本不是的关系。

## 初步的想法
* 先尝试把游侠和 3DM 的汉化包合并下，取一个合集
* 合并时，可以考虑选择较好的结果（暂时考虑按照文字长度来）
* 即使没有翻译的内容，考虑保留英文原版（至少不会搞不清楚再说什么）
* 合并的结果，放在 GitHub 上，因为都是纯文本，还有对照，大家可以踊跃修改
        * 各个汉化包合并好的总表
        * 官方 excel 版本追加好汉化内容的表格

## 目前的进度
* 之前从不同渠道收集的几个汉化包，已经尝试合并完了
* 挑选较优的内容，追加到官方 excel 中 
* 合并了游侠最新的3.5版本以及 3DM 最新的5.0版本
* 生成一个能用的版本

## excel 目录
       存放了添加翻译的excel，做为下次翻译的基础
       
## mod 目录
       生成的 string table，直接 copy 到游戏目录
       *需要自己 copy 一个 xml 文件*

## 参考
* 官方汉化工具说明页:http://forums.obsidian.net/topic/83837-update-104-last-chance/

## 关于版权
*感谢游侠和 3DM 的汉化。*
*我只是搬运工*
