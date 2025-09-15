# Applied AI for Enterprise Java — Examples

This repository contains the example code for *Applied AI for Enterprise Java Development* by **Alex Soto Bueno, Markus Eisele, and Natale Vinto** (O’Reilly, Nov 2025).  
The examples bring the book’s concepts to life, showing practical implementations of AI-infused Java applications with Quarkus, LangChain4j, vector stores, inference APIs, and more.

📖 Book page: [Applied AI for Enterprise Java Development (O’Reilly)](https://www.oreilly.com/library/view/applied-ai-for/9781098174491/)

## What’s in this Repo

- Complete example projects, organized per chapter.  
- Code illustrating patterns like **prompt engineering, RAG, caching, guardrails, fault tolerance**, and **enterprise AI architecture**.  
- Supporting configs, tests, and container setups for local runs.  

The repository is a **companion resource**: follow the book → explore the chapter code → experiment with variations.

## Getting Started

Clone this repository:

```bash
git clone https://github.com/applied-aI-for-enterprise-java-book/examples.git
cd examples
````

Then explore chapter examples, e.g.:

```bash
cd ch05
./mvnw quarkus:dev
```

> ⚠️ Some examples may require environment variables, API keys, or containerized services. See the individual chapter’s README for details.

## Repository Layout

The repo mirrors the chapters in the book:

```
/
├── ch05/   # Chapter 5 examples
├── ch07/   # Chapter 7 examples
├── ch08/   # Chapter 8 examples
├── ch09/   # Chapter 9 examples
├── ch10/   # Chapter 10 examples
├── ch11/   # Chapter 11 examples
└── .quarkus/cli/plugins/   # Supporting files
```

Each folder is self-contained with its own build file and instructions.

## Prerequisites

* **Java 17+** (some chapters may target newer versions)
* **Maven** (wrapper scripts included)
* **Docker / Podman** (for vector DBs, local models, etc.)
* Internet access for examples that call external APIs

## How to Use the Examples

1. Read the chapter in the book.
2. Open the corresponding folder in this repository.
3. Build and run the example using Maven or your IDE.
4. Modify parameters, prompts, or model configs to see how the system behaves.

The examples are meant to be a **playground for experimentation**, not just static code.

## Contributing

Contributions are welcome!

* **Issues**: report bugs, missing steps, or mismatched code.
* **Pull Requests**: add improvements, clarifications, or fixes.
* **Discussions**: suggest new directions or additional demos.

Please align changes with the book’s content and add documentation/tests when possible.

## License & Acknowledgments

* Code is provided under [Apache 2.0 License](LICENSE) (unless stated otherwise).
* Based on *Applied AI for Enterprise Java Development* by Alex Soto Bueno, Markus Eisele, and Natale Vinto.
* Thanks to the readers, contributors, and community members who extend these examples.

## Book Information

|                      |                                              |
| -------------------- | -------------------------------------------- |
| **Title**            | *Applied AI for Enterprise Java Development* |
| **Authors**          | Alex Soto Bueno, Markus Eisele, Natale Vinto |
| **Publisher**        | O’Reilly Media                               |
| **Publication Date** | November 2025                                |
| **ISBN**             | 9781098174491                                |
| **Level**            | Intermediate–Advanced                        |

We hope these examples help you build robust, AI-infused applications in the enterprise Java ecosystem.
**Happy coding! 🚀**
