上传的信息包括

{
	entry: "main",
	args: ["--test"],
	working_dir： "./",
	git_user: "thu-coai",
	git_repo: "cotk",
	git_commit: "dc06595bfbf381e2d35ec29df5538bf5f242d891",
	record_information: {
		type: ["LanguageGeneration_teacher_forcing",
		"LangaugeGeneration_inference"] 可能有多个type
	}
	result: {
		self-bleu: 123
		self-bleu hashvalue: "XXXX"
	}
}

根据type显示 主要结果

LanguageGeneration_teacher_forcing

	perplexity
    perplexity hashvalue

LanguageGeneration_inference
	self-bleu  
	self-bleu hashvalue  
    fw-bleu  
	bw-bleu  
    fw-bw-bleu  
    fw-bw-bleu hashvalue  


SingleTurnGeneration_teacher_forcing

	perplexity
    perplexity hashvalue

SingleTurnGeneration_inference

	bleu  
	bleu hashvalue  
    
MultiTurnGeneration_teacher_forcing

	perplexity
    perplexity hashvalue

SingleTurnGeneration_inference

	bleu  
	bleu hashvalue  

也允许用户自己定义需要显示的key，不存在该key的记录在位置上显示null即可。