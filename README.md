# Guilherme Hoffmann

AI engineer based in Curitiba, Brazil. I build agentic RAG and evaluation systems in **Python**, backed by 4+ years of production software engineering in **TypeScript, Node.js, PostgreSQL and AWS**. Co-founder of **Lex**, a legal practice management SaaS for Brazilian lawyers with an AI assistant and a RAG module over legal documents. Databricks Fundamentals accredited.

## Featured projects

- **Precursor**: agentic product-safety signal detection over 792,953 NHTSA vehicle complaints. It looks for emerging defect patterns before they become recalls, then investigates each signal with a LangGraph agent whose every claim cites real complaints, checked in code. Judged by a leakage-free backtest: recalls are the labels, every query runs "as of" a past date, and the headline numbers come from years no parameter was tuned on. Runs on a 16 GB Mac. *(Python, LangGraph)*
- **Agentic Corrective RAG**: question answering that grades its own evidence before it answers. Hybrid retrieval (dense + BM25) in Qdrant, an LLM grader, query rewriting with a bounded retry budget, abstention when evidence is missing, and citations validated mechanically. Evaluated against a plain RAG baseline with RAGAS, with the negative result reported honestly. *(Python, LangGraph, Qdrant, FastAPI, Streamlit, Langfuse, RAGAS, Docker)*

## What I'm working on

- **Lex**: AI-assisted workflows for lawyers, in production with about 10 law firms *(React, TypeScript, PostgreSQL/Supabase)*
- **Tink** (in development): a shared workspace where marketing teams talk to the same AI agent in a single conversation

## Stack

Python · LangChain · LangGraph · Qdrant · RAGAS · Langfuse · FastAPI · TypeScript · Node.js · React · Next.js · PostgreSQL · Supabase · AWS (S3, Lambda) · Docker · GitHub Actions

## Contact

guihoffmann7@gmail.com · Fluent in English and Portuguese · Open to remote AI Engineer roles
