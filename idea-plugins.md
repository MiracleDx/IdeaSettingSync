# Idea 插件清单

| 插件 | 用途 |
| --- | --- |
|.ignore| git ignore| 
| Alibaba Java Coding Guidelines | 阿里巴巴编码规范插件 |
| CodeGlance |  代码区右侧预览图插件 |
| Free MyBatis plugin | Mybatis使用助手插件 |
| GenerateAllSetter | 快速生成所有Setter插件 |
| GsonFormatPlus | 解析JSON为实体类插件 |
| IDEA Restart | IDEA重启插件 |
| Key Promoter X | 快捷键提示插件 |
| Lombok | lombok 插件 |
| Maven Helper | Maven依赖助手 |
| MyBatisLogFormat | Mybatis 日志拼装参数-SQL插件 |
| Nyan Progress Bar | 进度条样式插件 |
| Rainbow Brackets | 彩色括号插件 |
| RestfulToolkit | 快速查询Restful API 插件 |
| String Manipulation | 字符串处理插件 |
| Translation | 谷歌翻译插件 |
| CamelCase | 转换驼峰插件 |
| Grazie | 语法检查插件 |
| jclasslib Bytecode viewer | 字节码查看插件 |
| Auto filling Java call arguments | 自动填充Java方法默认参数插件 |
| Java Stream Debugger | Stream Debugger插件 |
| Python | Python支持插件 |
| Vue | Vue支持插件 |
| Codota | Codota支持插件 |
| Git Commit Template | Git提交模板插件 |
| GitToolBox | Git工具箱插件 |
| arthas idea | arthas工具插件 |
| Momo Code Sec Inpect | Momo检查Web安全插件 |
| SonarLint | bug检查插件 |
| Atom Material Icons | 图标插件 |
| Extra Icons | 图标插件 |

# Git 提交规范

`<type>: <subject>`

###### type
用于说明 commit 的类别，只允许使用下面7个标识。

`feat`：新功能（feature）   
`fix`：修补bug   
`docs`：文档（documentation）   
`style`： 格式（不影响代码运行的变动）   
`refactor`：重构（即不是新增功能，也不是修改bug的代码变动）   
`test`：增加测试   
`chore`：构建过程或辅助工具的变动   

*如果type为`feat`和`fix`，则该 commit 将肯定出现在 Change log 之中。*

###### subject
subject是 commit 目的的简短描述，不超过50个字符，且结尾不加句号（.）
