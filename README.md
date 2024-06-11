---
language:
- zh
- en
tags:
- Chatglm4_api_adaption
pipeline_tag: text-generation
inference: false
---
# Chatglm4_api_adaption
## 快速使用（Quickstart）
About
adapt Chatglm3 to load glm-4-9b-chat (Tool has some bugs)
# Change here and use
MODEL_PATH = os.environ.get('MODEL_PATH', 'glm-4-9b-chat')
MODEL_PATH = os.environ.get('MODEL_PATH', 'glm-4-9b-chat-int4')
TOKENIZER_PATH = os.environ.get("TOKENIZER_PATH", MODEL_PATH)

# set Embedding Model path
EMBEDDING_PATH = os.environ.get('EMBEDDING_PATH', 'xxxxxx')
