# Language Models

- [Text slides](https://docs.google.com/presentation/d/1ZvNFZUnm4TcBLMPxKBEtPUD71DEBQz5ObXUVsA-gamA/edit?usp=sharing)
- [LLM slides](https://docs.google.com/presentation/d/1n3eTpVpR281ppYdCW9xGoSpmMiDYjQU20lHWTp-t3VI/edit?usp=sharing)

## Transformers and Large Language Models

> among the reasons I use large pre-trained language models sparingly in my computer-generated poetry practice is that being able to know whose voices I'm speaking with is... actually important, as is being understanding how the output came to have its shape - [@aparrish](https://twitter.com/aparrish/), [full thread](https://twitter.com/aparrish/status/1286808606466244608)

- 📚 [Watch an A.I. Learn to Write by Reading Nothing but **\_\_\_\_**](https://www.nytimes.com/interactive/2023/04/26/upshot/gpt-from-scratch.html) by Aatish Bhatia
- 📚 [Attention is All You Need](https://arxiv.org/abs/1706.03762) - Original "Transformer" paper from 2017, also [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/abs/1409.0473) -- Attention paper from 2014
- 📚 [What Are Transformer Models and How Do They Work?](https://docs.cohere.com/docs/transformer-models)
- 🎥 [How large language models work, a visual intro to transformers](https://youtu.be/wjZofJX0v4M) by 3Blue1Brown
- 🎥 [Intro to Large Language Models](https://youtu.be/zjkBMFhNj_g) by Andrej Karpathy and [Intro to LLMs slides](https://drive.google.com/file/d/1pxx_ZI7O-Nwl7ZLNk5hI3WzAsTLwvNU7/view)
- 📖 [Language Models Can Only Write Ransom Notes](https://posts.decontextualize.com/language-models-ransom-notes/) by Allison Parrish

## LLM Training

- 🦙 [LLaMA: Open and Efficient Foundation Language Models](https://arxiv.org/pdf/2302.13971.pdf)
- 🦙 [The Llama 3 Herd of Models](https://arxiv.org/pdf/2407.21783)
- 🦜 [On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? 🦜](https://dl.acm.org/doi/10.1145/3442188.3445922)
- 🔍 [The Foundation Model Transparency Index](https://crfm.stanford.edu/fmti/May-2024/index.html)
- 📖 [Generative AI’s Illusory Case for Fair Use](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4924997) by Jacqueline Charlesworth

### Datasets for LLMs

- 🔢 [Common Crawl](https://commoncrawl.org/)
- 🔢 [The Pile](https://pile.eleuther.ai/)

### Climate Impact

- 🌏 [The Internet’s Next Great Power Suck](https://www.theatlantic.com/technology/archive/2023/08/ai-carbon-emissions-data-centers/675094/)
- ⚡️ [Carbon Emissions and Large Neural Network Training ](https://arxiv.org/ftp/arxiv/papers/2104/2104.10350.pdf)

## Code Examples
- [Word2Vec suggesting alternative words](https://editor.p5js.org/yining/sketches/AqFZmpoAX)
- [Word2vec Similar Words Floating in Space](https://editor.p5js.org/yining/sketches/_Ki2jFoJB)
- [Sentiment](https://editor.p5js.org/ml5/sketches/hopIvsCGL)
- [OpenAI API + p5.js](https://editor.p5js.org/yining/sketches/cnlmIOoL9)
- [Gemini API + p5.js drawing](https://x.com/alexanderchen/status/1819939988676440241), [code](https://editor.p5js.org/golan/sketches/7k4imWAs1)

### How to obtain a Google AI Studio developer test API key:
1. Go to the Google AI Studio website: https://ai.google.dev/aistudio
2. Sign in with your Google account
3. Navigate to the API Keys section (the blue "Get API Key" button on the top left)
4. Click on the "Create API Key" button
5. Follow the prompts to create a new project or select an existing one.
6. Enable the Gemini API for your project.
7. Copy the generated API key and paste it into the "API KEY" input field in the web application.
 * Note: Make sure to keep your API key secure and avoid sharing it publicly.

Example gemini curl [link](https://ai.google.dev/api?_gl=1*13fjlsq*_up*MQ..&gclid=Cj0KCQjwvJHIBhCgARIsAEQnWlBzobG9FGFMvlC68nlRVRo5l-QNBKwumub-Kfv_ibg9ekitbyyxTl4aAmJmEALw_wcB&gclsrc=aw.ds&gbraid=0AAAAACn9t66myntjHn7cE8bAgpYlsRE0g)

[Gemini api p5js](https://editor.p5js.org/yining/sketches/cyjAvH2uO)

## Assignment

- Use Gemini APIs to build any experience with p5.js, [example](https://github.com/ml5js/Intro-ML-Arts-IMA-F25/blob/main/09-llms/README.md#code-examples)
- Or try chat with [Gemini](https://gemini.google.com/app), [Google AI studio](https://aistudio.google.com/prompts/new_chat), [Chatgpt](https://chatgpt.com/), [Claude](https://claude.ai/new) and document your findings. 
- Or add more features to the [Word2Vec/Sentiment sketch](https://github.com/ml5js/Intro-ML-Arts-IMA-F25/blob/main/09-llms/README.md#code-examples).
- Document your experminents in a blog post and add a link to the [Assignment Wiki page](https://github.com/ml5js/Intro-ML-Arts-IMA-F25/wiki/Assignment-9). Remember to include visual documentation (screenshots, GIFs, etc)
