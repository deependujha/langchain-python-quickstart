# LangChain - quickstart (python) 🔥🚀

## Langchain 🦜⛓️

LangChain is a framework for developing applications powered by language models. We believe that the most powerful and differentiated applications will not only call out to a language model via an API, but will also:

- **Be data-aware**: connect a language model to other sources of data

- **Be agentic**: allow a language model to interact with its environment

The LangChain framework is designed with the above principles in mind.


---

## Components

There are several main modules that LangChain provides support for. For each module we provide some examples to get started and get familiar with some of the concepts. Each example links to API documentation for the modules used.

These modules are, in increasing order of complexity:

> **Schema**: This includes interfaces and base classes used throughout the library.

> **Models**: This includes integrations with a variety of LLMs, Chat Models and Embeddings models.

> **Prompts**: This includes prompt Templates and functionality to work with prompts like Output Parsers and Example Selectors

> **Indexes**: This includes patterns and functionality for working with your own data, and making it ready to interact with language models (including document loaders, vectorstores, text splitters and retrievers).

> **Memory**: Memory is the concept of persisting state between calls of a chain/agent. LangChain provides a standard interface for memory, a collection of memory implementations, and examples of chains/agents that use memory.

> **Chains**: Chains go beyond just a single LLM call, and are sequences of calls (whether to an LLM or a different utility). LangChain provides a standard interface for chains, lots of integrations with other tools, and end-to-end chains for common applications.

> **Agents**: Agents involve an LLM making decisions about which Actions to take, taking that Action, seeing an Observation, and repeating that until done. LangChain provides a standard interface for agents, a selection of agents to choose from, and examples of end-to-end agents.
