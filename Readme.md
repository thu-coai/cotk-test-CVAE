# 说明
*	git repo的根目录下有文件result.json，格式如下：
```
{
	working_dir: 程序运行的目录（相对于repo根目录）
	entry：入口程序文件名，如run，{{entry}}.py中包含入口函数run，接收参数列表
	args：入口函数接收的参数，list
	... # 测试结果，如bleu、perplexity等
}
```
*	运行python {{entry}}.py {{args}}后应当输出result.json
