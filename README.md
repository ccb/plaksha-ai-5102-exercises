# AI 5102 — Hands-On Exercises

**Introduction to Large Language Models and Generative AI**
Plaksha University · August 2026 · Chris Callison-Burch

These are the hands-on exercise notebooks for the course. Click an **Open in Colab**
badge, then immediately choose **File → Save a copy in Drive** so your work is saved
to your own Google Drive.

| # | Exercise | Open |
|---|----------|------|
| 1 | Language Model APIs | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ccb/plaksha-ai-5102-exercises/blob/main/exercise1_language_model_apis.ipynb) |
| 2 | Prompt Engineering and In-Context Learning | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ccb/plaksha-ai-5102-exercises/blob/main/exercise2_prompting_and_icl.ipynb) |
| 3 | Semantic Search with Embeddings | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ccb/plaksha-ai-5102-exercises/blob/main/exercise3_semantic_search.ipynb) |
| 4 | K-Nearest Neighbors and Retrieval Augmented Generation | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ccb/plaksha-ai-5102-exercises/blob/main/exercise4_rag_system.ipynb) |
| 5 | AI Agent with Tool Use (ReAct) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ccb/plaksha-ai-5102-exercises/blob/main/exercise5_react_agent.ipynb) |
| 6 | Be the Annotator: RLHF Preference Ranking and Reward Models | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ccb/plaksha-ai-5102-exercises/blob/main/exercise6_rlhf_annotation.ipynb) |

There are also lecture demo notebooks (shown live in class, no student TODOs —
just run them to see the ideas work step by step):

| Demo | Session | Open |
|------|---------|------|
| Word Embeddings (similarity, analogies, bias) | 4 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ccb/plaksha-ai-5102-exercises/blob/main/demo_word_embeddings.ipynb) |
| Function Calling (stock-price tool, 3 acts) | 6 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ccb/plaksha-ai-5102-exercises/blob/main/demo_function_calling.ipynb) |

## Before you start

1. **Get a free NVIDIA API key**: go to [build.nvidia.com](https://build.nvidia.com/),
   create an account, and generate an API key (Settings → API Keys). No credit card needed.
   Exercises 1, 2, 4, and 5 use it. Guard it like a password.
2. **Exercise 3 needs no API key** — everything runs locally in Colab.
3. Work top to bottom; run the given cells (later exercises depend on them), and only
   edit the cells marked **STUDENT INPUT** / **STUDENT TODO**.
4. If an API call fails: check your key, then the model string, then simply retry —
   transient errors are normal.

## A note on pace

- Exercise 2's model×strategy grid makes ~100 API calls and can take **20–45 minutes**
  on the free tier — start it, then work on the written exercises while it runs.
- Exercise 3 downloads embedding models (~1.5 GB) on first run; give the setup cells
  a few minutes.

These notebooks are ungraded, hands-on exercises — the goal is that you leave each
session having made real API calls, built a working chatbot, retriever, or agent, and
hit the failure modes yourself. Bring questions to the next session.
