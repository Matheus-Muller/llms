# llm
### LLMs studies
In this repository, I will share my notes and code examples related to Large Language Models (LLMs). The focus of these studies is on exploring practical applications of LLMs in solving real-world problems.

# Theory

## Types of prompts
- **System prompt**: Tells them what task they are performing and what tone they should use.
- **User prompt:** The conversation starter that they should reply to.

## Messages Template
The API expects to receive messages in a particular structure (list of dictionaries), like:

[
	{"role": "system", "content": "system message"},
	{"role": "user", "content": "user message"}
]

