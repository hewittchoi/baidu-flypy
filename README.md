# baidu-flypy
百度输入法挂接小鹤双拼+双形(小鹤音形)

主体部分来自 @fanqi 的sogou-flypy https://github.com/fanqi/sogou-flypy?_pjax=%23js-repo-pjax-container 共有52883个词条，与电脑版小鹤音形系统词库58018个词条有一定出入，但是由于不能导出，将就用。
在此基础上，将下面词库加入  
*-增补  
*-补充简码  
*-自己整理的四字成语  
# 方案一：导入个性短语
一、手机端：下载cphrase.ini，手机百度输入法-高级设置-管理个性短语-导入个性短语，设置个性短语位置为第一位，不能四码上屏，配合手机百度小鹤双拼(其他也行，短语置顶了不影响)确定单字  
已经保留百度输入法自带的短语，可在编辑个性短语中开启或关闭各分组。  
二、电脑端：下载“电脑版百度输入法个性短语-flypy.txt”，设置属性-更多-自定义短语设置-导入

# 方案二：导入自定义输入方案-可四码上屏（仅手机端）

下载bd-flypy.def，手机百度输入法-高级设置-管理自定义输入方案-删除自定义输入方案-导入自定义输入方案。  
这种方法需删除自定义输入方案，即自带的五笔方案，因此键盘也是选择五笔键盘。  
由于增加了四字成语，因此重码增加了，不想用可选择bd-flypy(not-include -si-zi).def  
用PlumTool.exe工具转换成词库，需是ANSI格式，原码表格式为[字符][编码]，无任何分隔符，你也可以自己制作。  




