# Vertex Engine - Solana AI Agents Creating Framework

Vertex is a powerful, modular, and highly extensible framework designed for developers building applications that require a seamless blend of performance, flexibility, and scalability. With vertex, you can harness the power of modern tools to craft cutting-edge solutions across industries.

---

## Contract Address and Development Funding
This project is powered by a single, official smart contract address. Please ensure that you interact only with the following address to avoid fraud or misrepresentation:

Contract Address: 
-----------------------------------

All development and maintenance of this project are funded exclusively through the creator's wallet associated with the token.

## Key Features
### 🚀 Exceptional Performance
Vertex is engineered for maximum speed and efficiency, ensuring seamless operation even during peak demand.

### ⚙️ Modular by Design
The modular architecture of Vertex lets you integrate only the essential components, keeping your applications streamlined and efficient.

### 📈 Seamless Scalability
From small projects to enterprise-level systems, Vertex evolves alongside your application, scaling effortlessly to meet growing demands.

### 🔒 Prioritized Security
Security is at the core of Vertex, offering powerful tools to protect your application and user data.

### 🧩 Limitless Extensibility
Easily enhance and customize Vertex with plugins, libraries, and APIs, shaping it to fit your unique project requirements.

## Getting Started

First install the package via PyPi.
```bash
pip install vertex-agents-py
```
Then define your agent, give it the tools it needs and run it!
```py
from vertex import CodeAgent, DuckDuckGoSearchTool, HfApiModel

agent = CodeAgent(tools=[DuckDuckGoSearchTool()], model=HfApiModel())

agent.run("How beneficial could the AI agents be to the humanity?")
```


## Contributing
We welcome contributions! If you want to report a bug, suggest a feature, or contribute code, please:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Submit a pull request.

## How strong are open models for agentic workflows?

We've created `CodeAgent` instances with some leading models, and compared them on [this benchmark](https://huggingface.co/datasets/m-ric/agents_medium_benchmark_2) that gathers questions from a few different benchmarks to propose a varied blend of challenges.

## Citing vertex

If you use `vertex` in your publication, please cite it by using the following BibTeX entry.

```bibtex
@Misc{vertex,
  title =        {`vertex`: The easiest way to build efficient solana agentic systems.},
  author =       {vertexngine inc.},
  howpublished = {\url{https://github.com/vertexngine/vertex}},
  year =         {2025}
}
```
