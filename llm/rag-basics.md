# RAG 基础

## 1. 定义
RAG（Retrieval-Augmented Generation）是检索增强生成：先从外部知识库检索相关内容，再把检索结果交给大模型生成答案。

## 2. 为什么重要
- 降低幻觉
- 支持知识更新
- 便于来源追溯

## 3. 在我的项目里怎么用
SmartDine 用 RAG 检索菜单、套餐、优惠规则和 FAQ。

## 4. 面试官可能怎么追问
- RAG 和微调有什么区别？
- embedding 和 reranker 有什么区别？
- top-k 怎么选？

## 5. 当前我的回答
- RAG 更适合知识更新快的场景
- embedding 负责粗召回，reranker 负责精排
- top-k 需要结合任务和上下文长度实验确定
