# RAG
0210版
RAG with Langchain and Hugging Face
#使用hugging face databricks/databricks-dolly-15k数据库的context列 作为库建立FIASS文件
#下载hugging face中Intel/dynamic_tinybert模型到本地 作为本地llm模型

0227版
1.用PyMuPDF4LLM库，将公司年报提取为Markdown格式
2.利用公司标题、格式分割文本
3.利用embedding建立FAISS文件，保存到本地
4.similarity_search搜索最相近的前5条文本
5.在txt中扩大文本，搜集上下文作为后续llm输入
