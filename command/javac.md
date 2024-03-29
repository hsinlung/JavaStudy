```
用法: javac <options> <source files>
其中, 可能的选项包括:
@<filename>                  从文件读取选项和文件名
-Akey[=value]                传递给注释处理程序的选项
--add-modules <模块>(,<模块>)*
除了初始模块之外要解析的根模块; 如果 <module>
为 ALL-MODULE-PATH, 则为模块路径中的所有模块。
--boot-class-path <path>, -bootclasspath <path>
覆盖引导类文件的位置
--class-path <path>, -classpath <path>, -cp <path>
指定查找用户类文件和注释处理程序的位置
-d <directory>               指定放置生成的类文件的位置
-deprecation                 输出使用已过时的 API 的源位置
--enable-preview             启用预览语言功能。要与 -source 或 --release 一起使用。
-encoding <encoding>         指定源文件使用的字符编码
-endorseddirs <dirs>         覆盖签名的标准路径的位置
-extdirs <dirs>              覆盖所安装扩展的位置
-g                           生成所有调试信息
-g:{lines,vars,source}       只生成某些调试信息
-g:none                      不生成任何调试信息
-h <directory>               指定放置生成的本机标头文件的位置
--help, -help, -?            输出此帮助消息
--help-extra, -X             输出额外选项的帮助
-implicit:{none,class}       指定是否为隐式引用文件生成类文件
-J<flag>                     直接将 <标记> 传递给运行时系统
--limit-modules <模块>(,<模块>)*
限制可观察模块的领域
--module <module-name>, -m <module-name>
只编译指定的模块, 请检查时间戳
--module-path <path>, -p <path>
指定查找应用程序模块的位置
--module-source-path <module-source-path>
指定查找多个模块的输入源文件的位置
--module-version <版本>        指定正在编译的模块版本
-nowarn                      不生成任何警告
-parameters                  生成元数据以用于方法参数的反射
-proc:{none,only}            控制是否执行注释处理和/或编译。
-processor <class1>[,<class2>,<class3>...]
要运行的注释处理程序的名称; 绕过默认的搜索进程
--processor-module-path <path>
指定查找注释处理程序的模块路径
--processor-path <path>, -processorpath <path>
指定查找注释处理程序的位置
-profile <profile>           请确保使用的 API 在指定的配置文件中可用
--release <release>          针对特定 VM 版本进行编译。支持的目标: 6, 7, 8, 9, 10, 11
-s <directory>               指定放置生成的源文件的位置
-source <release>            提供与指定发行版的源兼容性
--source-path <path>, -sourcepath <path>
指定查找输入源文件的位置
--system <jdk>|none          覆盖系统模块位置
-target <release>            生成特定 VM 版本的类文件
--upgrade-module-path <path>
覆盖可升级模块位置
-verbose                     输出有关编译器正在执行的操作的消息
--version, -version          版本信息
-Werror                      出现警告时终止编译
```