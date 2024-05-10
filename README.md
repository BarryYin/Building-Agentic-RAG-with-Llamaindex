# Building-Agentic-RAG-with-Llamaindex
from deeplearning.ai by Jerry Liu, who is CEO at LlamaIndex

# 介绍

本课程来自deeplearning.ai
本人自学所用
会有部分注释、笔记、拓展

# 关于课程
该课程详细的介绍了Llamaindex是如何执行RAG的，从执行效果来看，Llamaindex已经配置了整套的RAG相关的文档加载、Embedding量化、以及查询和总结。
并且设定了Agent模式，可以自动依据查询的内容，自主选择最佳工具执行。

1. L0_ready.ipynb 检查配置文件
2. L1_Router_Engine.ipynb 自动选择调用查询引擎
3. L3_Building_an_Agent_Reasoning_Loop.ipynb 设置一个Agent，reason+rag
4. L4_Building_a_Multi-Document_Agent.ipynb 复杂的多文档Agent

# 安装
 需要先安装requirements.txt,采用清华源.

 pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple

 pip install -r requirements.txt

之后就可以运行L0-L4文件了。


# 更多资源
1. Custom agent:
https://docs.llamaindex.ai/en/stable/examples/agent/custom_agent/

2. Community-built Agents (LlamaHub):
https://llamahub.ai/?tab=agent

3. Advanced document parsing with LlamaParse:
https:/cloud.llamaindex.ai/

# 点赞
如果你觉得本pr不错，请给个Star

