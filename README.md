# study_record 📚
> 本仓库记录了我从 0 开始系统学习 **LangChain + RAG** 的完整过程，包含分步练习代码、核心API示例，是从理论到工程落地的学习轨迹。

---

## 📂 仓库结构
```
study_record/
├── LangChain/
│   ├── s01_langchain_llm_access.py
│   ├── s02_langchain_streaming_output.py
│   ├── s03_chat_model.py
│   ├── s04_chat_model_message_shortcut.py
│   ├── s05_embedding_model.py
│   ├── s06_prompt_template.py
│   ├── s07_few_shot_prompt_template.py
│   ├── s08_chat_prompt_template.py
│   ├── s09_chain_base.py
│   ├── s10_str_output_parser.py
│   ├── s11_json_output_parser.py
│   ├── s12_memory_temporary_chat.py
│   ├── s13_memory_long_term_chat.py
│   └── s14_memory_combined_temporary_long.py
│
└── RAG/
    ├── s01_CSVloader.py
    ├── s02_JSONLoader.py
    ├── s03_pyPDFLoader.py
    ├── s04_text_loader_recursive_splitter.py
    ├── s05_in_memory_vector_store.py
    ├── s06_external_vector_store.py
    ├── s07_vector_search_prompt_builder.py
    ├── s08_RunnablePassthrough.py
    ├── s09_combined_rag_chain.py
    ├── KnowledgeBaseService.py
    ├── vector_stores.py
    ├── config_data.py
    ├── file_history_store.py
    ├── final_rag_with_chat_history.py
    ├── app_file_uploader.py
    └── app_qa.py
```



## 💡 仓库说明
- 所有 `sXX_*.py` 文件均为**分步学习记录**，按序号递进，对应从基础到进阶的知识点
- 文件名清晰标注了核心功能，方便快速定位学习内容
- 实战文件（如 `final_rag_with_chat_history.py`、`app_qa.py`）是多个知识点整合后的可运行 Demo
- 仓库不包含运行生成的缓存文件（如 `.idea/`、`chroma_db/`、`__pycache__/` 等），仅保留学习过程的核心代码
