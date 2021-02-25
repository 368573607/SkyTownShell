#  SkyTown Shell 命令语法稿 v1.0.0.0

1. {用于输出，>后的参数表示文件名},`'echo' [text:String] ['>' filePath:String]`
   * text: 输出的内容（可选）
   * filePath: 输出到的文件目录及文件名（可选）
2. {编辑文件},`'vim' filePath:String [-option1] [-option2] [-option3] [...]`
   * filePath: 文件目录及文件名
   * options: 提供的参数
      * `-o`:覆盖式写入（直接用新的替换旧的）
      * `-e`:追加式写入
      * `-s`:在头部写入
3. {只读模式查看文件},`'view' filePath:String`
   * filePath: 文件目录及文件名
4. {创建文件夹},`'mkdir' dirPath:String`
   * dirPath: 目录名
5. {打开文件夹},`'cd' dirPath`
   * dirPath: 目录名
6. {列出所有目录},`'ls'`
7. {关闭终端},`'exit'`
8. {拷贝文件},`'cp' parent:String target:String`
   * parent: 原文件
   * target: 目标文件
9. {创建文本文件},`'tcr' name`（touch create raw）
   * name: 文件名
10. {显示目录结构},`'tree'`
11. {显示用户信息},`'w'`
12. {显示版本},`'ABOUT'`
13. {操作变量},`name = value`
    	* name: 变量名
    	* value: 值
14. {重命名文件},`'ren' fileName targetName`
    	* fileName: 待重命名的文件的文件名
    	* targetName: 目标文件名
15. {删除文件},`'remove' fileName`
16. {删除文件夹},`'redir' dirName`