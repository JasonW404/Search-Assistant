# Search Assistant

## Description

This is a simple search assistant tool that can be used to generate search keywords for a given text.

## Before running the code

This project depends on some tools, so you need to properly install and configure them before running the code.

### LangChain

You can install **LangChain** and relative pakages used in this project by running the following command:

```bash
pip install langchain langchain_ollama
```

### Ollama

You can install **Ollama** by downloading the latest release from [here](https://ollama.com/download).

After installing **Ollama**, you need to pull the `Gemma2-2B` model by running the following command:

```bash
ollama pull gemma2:2b
```

### Jypter Notebook Related

I used some Jupyter Notebook related tools in this project, so you need to install them by running the following command:

```bash
pip install jupyter ipywidgets
```

## Give it a try!

You can run the code by opening the `main.ipynb` file in Jupyter or VS Code and running the cells one by one.

**That's it!**

---

## License

Nothing worth licensing here, so feel free to use it as you like.

Thanks to Ollama and LangChain.
