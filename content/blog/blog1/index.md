---

title: "Ollama and OpenWebUI: Using local LLMs" 
date: 2025-09-02
tags: ["Blog", "Local LLM", "generative AI"]
author: ["Jade Suiyue Yue van Dorth"]
description: "This blog details how you can locally run LLMs using Ollama and OpenWebUI." 
summary: "This blog briefly describes how you can locally run LLMs using Ollama and OpenWebUI. It may be useful for personal tasks or research in the future." 
showToc: true
disableAnchoredHeadings: false

---

## Getting started, you can do it too!

"How would I ever program a Large Language Model (LLM) myself? I have no coding experience!"

Well, I didn't have much experience with coding either, aside from HTML, CSS and JavaScript I learned in high school. However, for my Master's thesis, I was determined on a topic related to generative AI and as such, felt that it was time for me to learn how to use LLMs in a responsible way, for the sake of writing a strong thesis. Besides, it seemed like a valuable quest, trying to figure out how researchers may be able to use LLMs responsibly. Please don't let the lack of coding experience or computer knowledge hold you back from trying! If I can do it, you can surely do it too! 

As I wanted to find a responsible way of using LLMs, I asked a friend of mine (whom I would like to call a computer nerd) and he suggested me to check out local LLM deployment. 

---

## Local LLMs, the pros and cons

Alright, I hear you. You might now be thinking: "Local LLM? But can't I just use ChatGPT (or something similar)?". Well, that's a possibility yes. LLMs are everywhere now, but you’ve got two main ways to use them: run one locally on your own device or rely on a commercial service.

Let me be clear: I don't want to discourage people from interacting with commercial LLMs, but I hope that people can come to understand *why* local LLMs are also great! 

#### Pros
- Full privacy: your data never leaves the computer.
- No subscription fees.
- You can tweak and customize.
- Works offline.

#### Cons
- Needs beefy hardware for bigger models. 
- Setup can be technical and a bit intimidating. 
- Performance may lag behind commercial giants. 

For many of us, including researchers, privacy really matters. With local LLMs, we can thus explore this new technology without handing over too much data to commercial services. 

---

## Ollama and OpenWebUI, simple setup

Okay, before you get started with the setup, you might want some more information on *what* you'll be putting on your computer.  
- Ollama is a powerful open-source tool that simplifies downloading, installing, and running LLMs locally. Think of it as a friendly manager for AI models on your machine, letting you pick from popular models like Llama, Mistral, or CodeLlama without complicated setup. 
- OpenWebUI is a web-based interface that can connect to your local models, giving you a user-friendly chat window right in your browser (via localhost). It looks a bit similar to ChatGPT, and it definitely beats typing and reading in the Terminal. ;) 

For the most reliable and up-to-date information, I think it’s best to follow the official guides on Ollama and OpenWebUI GitHub repositories. While there are also various blog posts and instructional videos available, official documentation often gets updated first, so checking the original sources ensures you have the latest instructions!
- Ollama GitHub repository https://github.com/ollama/ollama
- OpenWebUI GitHub repository https://github.com/open-webui/open-webui

---

Alright, if you've followed all the steps correctly, you should be able to run your own LLM locally. I did indeed notice that for some models, the performance is a bit behind the commercial models. However, most of the (smaller) models available are more than capable of assisting with simple tasks - like planning household chores or organizing your study notes. 

That's all for now from me! I really hope that you'll give this a try! ;) 