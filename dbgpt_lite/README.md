# DB-GPT-Lite

1. 评估框架 ([dbgpt_lite/eval](eval))：评估大模型的基本性能（包括语言模型性能、NL2SQL模型性能、RAG性能）
2. 大模型推理部署框架 ([dbgpt_lite/inference](inference))：包括生产级的vllm和研发级的ollama + litellm
3. 大模型微调框架 ([dbgpt_lite/finetune](finetune))：进行指令微调、Embedding微调、检索器微调、生成器微调
4. 优质数据集生成及评估框架 ([dbgpt_lite/synthetic_data](synthetic_data))：实现优质数据自动筛选、训练样本数据自动生成、数据质量评估
5. AI应用试验平台 ([dbgpt_lite/web](web))：以DB-GPT-Lite为起点，构建统一的AI应用试验、评估平台

能力目标：

1. 完整的大模型应用试验能力，统一的技术架构可应对各种大模型、应用
2. 支持迭代开发大模型应用的模型及应用评估能力
3. 数据集管理能力提升，由收集模式上升至具备优质数据筛选、训练样本数据生成能力
