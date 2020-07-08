
* 功能：分析OC APP中哪些方法未被调用
* 使用方法：
 1. 编译ios工程，生成app，找到app中的mach-o二进制文件
 2. 执行：python objc_cover.py file(mach-o二进制文件)，会输出未使用的方法
  
 
