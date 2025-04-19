# A Comprehensive Overview of Large Language Models Since May 2024: OpenAI and Its Competitors

## Table of Contents

1.  [Introduction](https://www.google.com/search?q=%231-introduction)
    2.(\#2-openai-llms-released-since-may-2024)
    \*(\#gpt-4o)
    \*(\#gpt-4o-mini)
      * [o1](https://www.google.com/search?q=%23o1)
      * [o1-mini](https://www.google.com/search?q=%23o1-mini)
      * [o3](https://www.google.com/search?q=%23o3)
      * [o4-mini](https://www.google.com/search?q=%23o4-mini)
        \*(\#gpt-45)
        \*(\#gpt-41-family)
        \*(\#specialized-models-and-updates)
        \*(\#table-openai-llm-areas-of-excellence)
2.  [Comparative Analysis with Alternative LLMs](https://www.google.com/search?q=%233-comparative-analysis-with-alternative-llms)
    \*(\#claude-37-sonnet-anthropic)
      * [Grok-3 (xAI)](https://www.google.com/search?q=%23grok-3-xai)
      * [Gemini 2.0 (Google DeepMind)](https://www.google.com/search?q=%23gemini-20-google-deepmind)
        \*(\#deepseek-r1-and-v3-deepseek-ai)
      * [Mistral Large 2 (Mistral AI)](https://www.google.com/search?q=%23mistral-large-2-mistral-ai)
      * [Llama 3.1 (Meta AI)](https://www.google.com/search?q=%23llama-31-meta-ai)
      * [Phi-3 (Microsoft)](https://www.google.com/search?q=%23phi-3-microsoft)
      * [Amazon Nova (Amazon)](https://www.google.com/search?q=%23amazon-nova-amazon)
        4.(\#4-summary-table-of-openai-and-alternative-llm-benchmarks)
3.  [Conclusion](https://www.google.com/search?q=%235-conclusion)
    6.(\#6-references)

## 1\. Introduction

(\#table-of-contents)

The field of Large Language Models (LLMs) has witnessed remarkable progress in recent years, marked by a rapid increase in capabilities and a growing influence across various sectors. These sophisticated models have become integral to advancements in natural language processing, enabling significant strides in tasks such as text generation, language translation, and information retrieval. OpenAI has consistently been at the forefront of this technological evolution, particularly renowned for its development of the GPT series of models, which have set new standards for performance and versatility. However, the LLM landscape is becoming increasingly competitive, with major research organizations, technology corporations, and innovative startups introducing highly capable models that challenge OpenAI's dominance. This dynamic environment necessitates a continuous and detailed analysis to track the latest developments and to understand the relative strengths and specializations of the various LLMs available. This report aims to provide such an analysis, focusing specifically on the period since May 2024, a timeframe that has seen significant advancements and new model releases from OpenAI and its competitors.

The primary objective of this report is to offer a comprehensive overview of all Large Language Models (LLMs) released by OpenAI starting from May 2024. In addition to detailing these models and their specific strengths, this analysis will include a thorough comparative evaluation of OpenAI's offerings against alternative LLMs from other organizations that have been either released or significantly updated within the same period. This report adopts a technical and analytical approach, leveraging publicly available data, performance benchmarks, and documented capabilities to provide a robust assessment of the current LLM landscape. The intended audience for this report comprises individuals with a strong technical background in artificial intelligence and machine learning, including researchers, developers, and analysts seeking a detailed understanding of the state-of-the-art in LLM technology.

The methodology employed in this report involves a comprehensive review and synthesis of publicly accessible research materials. This includes technical documentation and system cards released by OpenAI and other organizations, announcements and blog posts detailing new model features and capabilities, and reported benchmark results from various industry-standard evaluations. The analysis will focus on extracting crucial technical specifications, key performance indicators, and the intended use cases for each identified LLM, thereby providing a detailed and data-supported comparison of their respective strengths and limitations.

## 2\. OpenAI LLMs Released Since May 2024

(\#table-of-contents)

A systematic review of the available information reveals a diverse and extensive portfolio of Large Language Models released by OpenAI starting from May 2024. This period has been characterized by a high frequency of new model introductions and updates, reflecting OpenAI's ongoing commitment to pushing the boundaries of AI capabilities. The models identified include GPT-4o [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39], GPT-4o mini [1, 2, 6, 8, 9, 13, 14, 15, 27, 30, 34, 35, 36, 37, 39, 40, 41], o1 [1, 2, 4, 5, 6, 8, 9, 10, 31, 33, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52, 53, 54, 55, 56, 57, 58, 59, 60], o1-mini [1, 2, 6, 8, 9, 31, 33, 36, 50, 52, 56, 58, 59, 60], GPT-4o mini Audio [9], GPT-4o Realtime [9], GPT-4o mini Realtime [9], GPT-4o mini TTS [9], GPT-4o Transcribe [9], GPT-4o mini Transcribe [9], o1-preview [8, 9, 33, 50, 55, 59, 60], o3-mini [1, 2, 4, 61, 5, 6, 8, 9, 10, 17, 28, 33, 42, 43, 50, 56, 57, 62, 63, 64, 65, 66, 67], o3 [1, 5, 6, 8, 9, 10, 28, 33, 42, 43, 44, 45, 46, 47, 48, 49, 68], o4-mini [1, 5, 6, 8, 9, 10, 28, 33, 34, 43, 44, 45, 46, 47, 48, 49, 57, 63, 64, 65, 66, 68], GPT-4.5 [1, 2, 61, 5, 6, 10, 11, 17, 29, 33, 41, 69, 70, 71, 72, 73, 74, 75, 76], GPT-4.1 [6, 9, 11, 17, 33, 41, 70, 77, 78, 79, 80, 81, 82, 83, 84], GPT-4.1 mini [6, 9, 17, 77, 80, 81, 82, 84], GPT-4.1 nano [6, 9, 17, 77, 80, 81, 82, 84], gpt-4o-search-preview [6, 9], gpt-4o-mini-search-preview [6, 9], computer-use-preview [6, 8, 9], gpt-4o-realtime [6], gpt-4o-audio [6], gpt-4o-audio-preview [6], chatgpt-4o-latest [1, 6], o3-pro [7], o3-mini-high [42], o3-mini-medium [42], o1-pro [9], gpt-4o-2024-08-06 [6, 16, 30, 79], gpt-4o-2024-11-20 [8, 16, 17, 28, 79], gpt-4o-2024-05-13 [8, 16, 79], o3 (2025-04-16) [8], o4-mini (2025-04-16) [8], o3-mini (2025-01-31) [8], o1 (2024-12-17) [8], o1-preview (2024-09-12) [8], o1-mini (2024-09-12) [8], gpt-4o (2024-11-20) [8], gpt-4o (2024-08-06) [8], gpt-4o-mini (2024-07-18) [8], gpt-4o (2024-05-13) [8], gpt-4.1 (April 14, 2025) [6], gpt-4.1-mini (April 14, 2025) [6], gpt-4.1-nano (April 14, 2025) [6], o3 (April 16, 2025) [6], o4-mini (April 16, 2025) [6], o3-mini (January 31, 2025) [6], GPT-4.5 (February 27, 2025) [1, 6], o3 and o4-mini (April 16, 2025) [1], o3-mini (January 31, 2025) [1], GPT-4o mini (July 18, 2024) [1], o1 (September 12, 2024) [1], o1-mini (September 12, 2024).[1] This extensive list highlights OpenAI's strategy of developing models with varying capabilities and cost structures to address a wide array of applications. The introduction of the "o" series signifies a dedicated effort towards enhancing the reasoning abilities of their models.

### GPT-4o

(\#table-of-contents)

**GPT-4o**, released on May 13, 2024 [18], stands out as a flagship model with native multimodal capabilities, processing and generating text, audio, and images.[12, 22] Its architecture involves a single end-to-end neural network, enabling faster response times and improved efficiency compared to its predecessors.[18] Key features include real-time audio conversation and enhanced understanding of non-English languages and vision.[12, 18, 23, 24, 25, 26] GPT-4o is intended for versatile applications requiring fast and intelligent responses across various modalities.[2]

### GPT-4o mini

(\#table-of-contents)

**GPT-4o mini**, launched on July 18, 2024 [1], is a smaller, faster, and more cost-efficient variant of GPT-4o.[9, 14, 37] It leverages a streamlined version of the GPT-4 architecture [40] and excels in tasks requiring speed and efficiency, such as coding, debugging, and real-time interactions.[14] Despite its compact size, GPT-4o mini demonstrates strong performance in multimodal reasoning and achieves impressive scores on academic benchmarks.[5, 34, 37]

### o1

(\#table-of-contents)

The **o1** model series, with the full version released on December 17, 2024 [8], represents a new generation of reasoning models designed to spend more time "thinking" before responding.[50, 55] This is achieved through large-scale reinforcement learning focused on chain-of-thought processing.[50, 51] o1 excels in complex reasoning tasks and demonstrates strong performance in STEM fields, including mathematics, coding, and science.[50, 53, 55] It also shows notable capabilities in cybersecurity.[51, 54]

### o1-mini

(\#table-of-contents)

**o1-mini**, released on September 12, 2024 [8], is a faster and more cost-effective version of o1, particularly effective at coding and other STEM tasks where broad general knowledge might not be essential.[58, 60]

### o3

(\#table-of-contents)

The **o3** model, released on April 16, 2025 [1, 6, 8], is described as OpenAI's most powerful reasoning model to date, excelling in complex queries requiring multi-faceted analysis and demonstrating state-of-the-art performance in coding, mathematics, science, and visual tasks.[5, 43, 68] It can integrate images directly into its chain of thought and agentically utilize tools like web search and Python.[5, 49, 68]

### o4-mini

(\#table-of-contents)

**o4-mini**, also released on April 16, 2025 [1, 6, 8], is a smaller model optimized for fast and cost-efficient reasoning, achieving remarkable performance for its size, especially in math, coding, and visual analysis.[5, 48] It is notable for being the best-performing benchmarked model on AIME 2024 and 2025.[5]

### GPT-4.5

(\#table-of-contents)

**GPT-4.5**, released as a research preview on February 27, 2025 [1, 6], is OpenAI's largest and most knowledgeable model for chat yet.[1, 61] It builds on GPT-4o by scaling pre-training and incorporates new supervision techniques.[72] GPT-4.5 demonstrates a broader knowledge base, improved ability to follow user intent, and greater "EQ," making it useful for tasks like improving writing, programming, and solving practical problems.[71, 73, 75] It also exhibits strong factual accuracy and hallucinates less than other OpenAI models.[71, 73]

### GPT-4.1 Family

(\#table-of-contents)

The **GPT-4.1** family of models, including GPT-4.1, GPT-4.1 mini, and GPT-4.1 nano, was launched on April 14, 2025.[6, 17, 77] These models outperform GPT-4o and GPT-4o mini across the board, with significant gains in coding and instruction following.[17] They also feature larger context windows, supporting up to 1 million tokens.[17, 82] **GPT-4.1** is the flagship model, optimized for complex tasks and excelling in software development, research, and agentic workflows.[80, 84] It shows substantial improvements in real-world software engineering skills and instruction accuracy.[80, 82, 84] **GPT-4.1 mini** offers nearly the same capabilities as the full model but with lower latency and cost, making it a balanced option for various use cases.[80, 84] **GPT-4.1 nano** is the fastest and most cost-effective model in this series, ideal for tasks like classification and autocompletion.[80, 84]

### Specialized Models and Updates

(\#table-of-contents)

In addition to these primary models, OpenAI has also released various specialized versions and updates, such as gpt-4o-search-preview and gpt-4o-mini-search-preview for web search, computer-use-preview for specific tool usage, and audio-related models like gpt-4o-audio-preview and gpt-4o mini TTS.[6, 9] These tailored offerings further illustrate OpenAI's strategy of providing a comprehensive suite of LLMs to meet diverse application requirements.

### Table: OpenAI LLM Areas of Excellence

(\#table-of-contents)

| OpenAI LLM Name | Areas of Excellence |
| :------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| GPT-4o | Real-time multimodal interaction, fast response times, improved performance in non-English languages |
| GPT-4o mini | Cost-effective intelligence, strong performance in math, coding, and visual reasoning for its size |
| o1 | Complex reasoning, solving hard problems in science, coding, and math, cybersecurity |
| o1-mini | Faster and more cost-effective reasoning for STEM tasks, especially math and coding |
| o3 | State-of-the-art reasoning, excelling in coding, mathematics, science, and visual perception |
| o4-mini | Fast and efficient reasoning, best-in-class performance on AIME for its size, strong in math, coding, and visual analysis |
| GPT-4.5 | Broad knowledge, improved ability to follow user intent, stronger "EQ", excels in writing and creative tasks, factual accuracy |
| GPT-4.1 | Significant gains in coding, instruction following, and long-context comprehension, multi-document Q\&A, reasoning on complex visual data |
| GPT-4.1 mini | Balanced intelligence, speed, and cost, instruction following, image-based reasoning |
| GPT-4.1 nano | Speed, cost-effectiveness, classification, autocompletion |
| gpt-4o-search-preview | Web search in Chat Completions |
| gpt-4o-mini-search-preview | Fast, affordable small model for web search |
| computer-use-preview | Specialized model for computer use tool |
| GPT-4o Audio | Audio inputs and outputs |
| GPT-4o mini Audio | Smaller model capable of audio inputs and outputs |
| GPT-4o Realtime | Realtime text and audio inputs and outputs |
| GPT-4o mini Realtime | Smaller realtime model for text and audio inputs and outputs |
| GPT-4o mini TTS | Text-to-speech |
| GPT-4o Transcribe | Speech-to-text |
| GPT-4o mini Transcribe | Speech-to-text |
| o1-preview | Early preview of the full o1 model, tackling complex problems requiring broad general knowledge |
| o3-mini | Cost-efficient reasoning, superior performance at low latency/cost, enhanced developer features, strong in science, math, and coding |
| o3-pro | Enhanced version of o3 |
| o3-mini-high | Variant of o3-mini with higher reasoning effort |
| o3-mini-medium | Variant of o3-mini with medium reasoning effort |
| o1-pro | Version of o1 with more compute for better responses |
| gpt-4o-2024-08-06 | Structured outputs, text, image processing |
| gpt-4o-2024-11-20 | Structured outputs, text, image processing, enhanced accuracy and responsiveness, superior performance in non-English languages and vision tasks, enhanced creative capabilities |
| gpt-4o-2024-05-13 | Text, image processing, enhanced accuracy and responsiveness, superior performance in non-English languages and vision tasks |
| o3 (2025-04-16) | Enhanced reasoning abilities, text, image processing |
| o4-mini (2025-04-16) | Enhanced reasoning abilities, text, image processing |
| o3-mini (2025-01-31) | Enhanced reasoning abilities, text-only processing |
| o1 (2024-12-17) | Enhanced reasoning abilities, text, image processing |
| o1-preview (2024-09-12) | Older preview version |
| o1-mini (2024-09-12) | Faster and more cost-efficient option in the o1 series, ideal for coding tasks requiring speed and lower resource consumption |

## 3\. Comparative Analysis with Alternative LLMs

(\#table-of-contents)

The LLM landscape extends beyond OpenAI, with several organizations releasing highly competitive models since May 2024. These alternative LLMs often rival or surpass OpenAI's offerings in specific areas, showcasing the rapid advancements and diverse approaches within the field.

### Claude 3.7 Sonnet (Anthropic)

(\#table-of-contents)

**Claude 3.7 Sonnet** from Anthropic, released in February 2025 [61, 85], is positioned as a highly intelligent model with state-of-the-art capabilities for coding and significant improvements in content generation, data analysis, and planning.[85, 86, 87] Benchmarks indicate that Claude 3.7 Sonnet excels in instruction following, achieving high scores on IFEval.[63] It also demonstrates strong performance in coding tasks, scoring competitively on the Aider polyglot benchmark.[62] Anthropic has stated that Sonnet is designed to outperform GPT-4o, making it a direct competitor in terms of intelligence and versatility.[2]

### Grok-3 (xAI)

(\#table-of-contents)

**Grok-3**, developed by xAI and unveiled in February 2025 [61, 64], represents a significant leap in reasoning capabilities, leveraging ten times more compute than its predecessor, Grok-2.[88, 89] Trained on xAI's Colossus supercluster, Grok-3 exhibits strong performance in STEM domains, achieving high accuracy on the AIME 2025 competition math (93.3%) and GPQA (84.6%) graduate-level reasoning benchmarks.[64, 65, 88] In coding, it scores impressively on LiveCodeBench (79.4%).[64, 65, 88] Grok-3 features a "Think" mode that allows it to refine answers through test-time computation, enhancing accuracy in complex analytical tasks.[64, 88, 90] Its performance on the LMSYS Arena leaderboard has also been notable, surpassing models like GPT-4o and Claude 3.5 Sonnet.[89, 91]

### Gemini 2.0 (Google DeepMind)

(\#table-of-contents)

Google DeepMind has continued to innovate with its **Gemini 2.0** family of models. Since May 2024, they have released or updated several variants, including **Gemini 2.0 Pro**, **Gemini 2.0 Flash**, and **Gemini 2.0 Flash-Lite**.[2, 3, 4, 61, 66, 92, 93, 94, 95, 96] These models are multimodal, capable of processing text, images, audio, and video inputs (with varying support across models) and generating text responses.[2, 92] A key advantage of the Gemini 2.0 family is their large context windows, with Flash and Pro versions supporting up to 1 million tokens.[3, 92, 93] Gemini 2.0 Pro is considered Google's best model yet for coding performance and complex prompts.[94] Benchmarks show that Gemini 2.0 Flash outperforms 1.5 Flash in reasoning, multimodal tasks, math, and factuality.[93, 94] Gemini 2.0 Flash-Lite is optimized for cost efficiency and low latency, offering improved performance over 1.5 Flash on several benchmarks, including SimpleQA and BirdSQL.[94] In coding tasks, Gemini 2.0 Flash has shown strong performance on LiveBench.[66]

### DeepSeek R1 and V3 (DeepSeek AI)

(\#table-of-contents)

**DeepSeek AI** has emerged as a strong contender, particularly with its **DeepSeek R1** and **DeepSeek V3** models.[4, 61, 97, 98, 99, 100, 101, 102] DeepSeek R1, released in January 2025, is a 671B parameter Mixture-of-Experts (MoE) model focused on reasoning capabilities, trained via large-scale reinforcement learning.[98, 99] It achieves performance comparable to OpenAI-o1 across math (MATH-500: 97.3%), code (Codeforces: 96.3% percentile), and reasoning tasks.[97, 98] DeepSeek R1 is designed to provide step-by-step reasoning, making it suitable for research and analysis.[100, 102] DeepSeek V3, released in December 2024, is also a 671B parameter MoE model but is optimized for broader performance across multiple NLP benchmarks while maintaining efficient training costs.[97, 98] It incorporates reasoning capabilities distilled from DeepSeek R1 and supports a 128K context window.[98, 99] Notably, DeepSeek V3 is significantly more cost-effective than DeepSeek R1 for API usage.[98, 99]

### Mistral Large 2 (Mistral AI)

(\#table-of-contents)

**Mistral AI** has continued to develop its range of models, with **Mistral Large 2** released in July 2024.[4, 61, 103, 104, 105, 106, 107] This model boasts top-tier reasoning capabilities and excels in advanced reasoning, multilingual tasks, mathematics, and code generation.[105] It features a 128K token context window and has shown strong performance on the MMLU benchmark (84.0% in a 5-shot scenario).[104, 107] Mistral Large 2 is also noted for its cost-effectiveness compared to some older models like GPT-4 32K.[107]

### Llama 3.1 (Meta AI)

(\#table-of-contents)

Meta AI has released **Llama 3.1** in July 2024, building upon the strengths of its predecessors with enhanced NLP performance and improved contextual understanding.[4, 61, 108, 109, 110, 111, 112, 113] The Llama 3.1 family includes models with 8B, 70B, and 405B parameters, with the 405B model demonstrating outstanding performance across a broad range of industry benchmarks, often rivaling or surpassing GPT-4 in some tests.[113] Specifically, Llama 3.1 405B achieves high scores on MMLU (88.6%), HumanEval (89.0%), and GSM8K (96.8%).[109, 111, 112] The model also excels in long-context tasks with a 128K token context window.[111]

### Phi-3 (Microsoft)

(\#table-of-contents)

Microsoft has introduced the **Phi-3** family of Small Language Models (SLMs) since April 2024, including models like Phi-3 mini, small, and medium, as well as the Phi-3.5 series.[4, 61, 114, 115, 116, 117, 118] These models are designed to be highly capable and cost-effective, often outperforming models of similar and larger sizes across various benchmarks in language, reasoning, coding, and math.[116] Phi-3 mini, with 3.8 billion parameters, achieves performance rivaling models like Mixtral 8x7B and GPT-3.5 on benchmarks like MMLU (69%) and MT-bench (8.38).[117, 118] The Phi-3.5 series further enhances capabilities, with Phi-3.5-mini supporting a 128K context length and improved multilingual support.[116] Phi-3.5-MoE, with 6.6B active parameters, delivers high performance in language understanding, math, and reasoning, often surpassing larger models.[116]

### Amazon Nova (Amazon)

(\#table-of-contents)

Amazon introduced its **Amazon Nova** models (Pro, Micro, Lite) at AWS re:Invent in December 2024.[4, 61, 27] These models are presented as cost-effective alternatives to OpenAI's offerings, particularly in retrieval-augmented generation tasks. While GPT-4o demonstrated a slight advantage in accuracy over Amazon Nova Pro on a subset of the CRAG benchmark dataset, Amazon Nova Pro outperformed GPT-4o in efficiency, operating 97% faster and being 65.26% more cost-effective.[27] Amazon Nova Micro and Amazon Nova Lite also showed competitive accuracy and cost-effectiveness compared to GPT-4o-mini.[27]

## 4\. Summary Table of OpenAI and Alternative LLM Benchmarks

(\#table-of-contents)

| Model Name | Organization | MMLU (%) | HumanEval (%) | AIME (%) | GPQA (%) | SWE-bench (%) | Context Window (Tokens) | Approx. Parameters (B) | Source(s) |
| :--------------------- | :---------------- | :------- | :------------ | :------- | :------- | :------------ | :---------------------- | :----------------------- | :------------------------- |
| GPT-4o | OpenAI | 88.7 | 90.2 | 9.3 | 53.6 | 33.2 | 128,000 | \~1.8T | [12, 32, 71] |
| Claude 3.7 Sonnet | Anthropic | N/A | N/A | N/A | N/A | N/A | 200,000 | \~175-200 | [2, 86] |
| Grok-3 | xAI | 92.7 | 86.5 | 93.3 | 84.6 | N/A | 128,000 | 2.7T | [88, 91] |
| Gemini 2.0 Pro | Google DeepMind | 81.9 | 71.9 | N/A | N/A | N/A | 2,097,152 | Unknown | [2, 32] |
| DeepSeek R1 | DeepSeek | 90.8 | N/A | 79.8 | 71.5 | N/A | 128,000 | 671 | [97, 98] |
| Mistral Large 2 | Mistral AI | 84.0 | N/A | N/A | N/A | N/A | 128,000 | 123 | [103, 104] |
| Llama 3.1 (405B) | Meta AI | 88.6 | 89.0 | 96.8 | 51.1 | 88.6 | 128,000 | 405 | [109, 111, 112] |
| Phi-3 Medium | Microsoft | 78.0 | N/A | N/A | N/A | N/A | 128,000 | 14 | [117] |
| Amazon Nova Pro | Amazon | 51.5 | N/A | N/A | N/A | N/A | 300,000 | Unknown | [27] |
| GPT-4.1 | OpenAI | N/A | 54.6 | N/A | N/A | 54.6 | 1,000,000 | Unknown | [17, 80] |
| o3 | OpenAI | 91.6 | N/A | 96.7 | 87.7 | 71.7 | 200,000 | Unknown | [5, 43] |
| o4-mini | OpenAI | 93.4 | N/A | 99.5 | 81.4 | 68.1 | 200,000 | Unknown | [5] |
| GPT-4.5 | OpenAI | 85.1 | 32.6 | 36.7 | 71.4 | 38.0 | 128,000 | Unknown | [71] |

## 5\. Conclusion

(\#table-of-contents)

The analysis of Large Language Models released since May 2024 reveals a period of intense innovation and rapid advancement within the field. OpenAI has continued to be a dominant force, introducing a diverse range of models, including the flagship multimodal GPT-4o, the cost-effective GPT-4o mini, the reasoning-focused o-series (o1, o3, o4-mini), and the high-performing GPT-4.1 family. These models demonstrate significant progress in areas such as multimodality, reasoning capabilities, and performance on various benchmarks, catering to a wide spectrum of applications and user needs.

However, the LLM landscape is increasingly competitive. Alternative LLMs from organizations like Anthropic (Claude 3.7 Sonnet), xAI (Grok-3), Google DeepMind (Gemini 2.0), DeepSeek (DeepSeek R1, V3), Mistral AI (Mistral Large 2), Meta AI (Llama 3.1), Microsoft (Phi-3), and Amazon (Amazon Nova) have emerged as strong contenders, often rivaling or surpassing OpenAI's models in specific domains. Claude 3.7 Sonnet demonstrates excellence in instruction following and coding. Grok-3 exhibits superior performance in math, science, and coding reasoning. Gemini 2.0 models offer extensive context windows and strong coding abilities. DeepSeek R1 excels in explainable reasoning and STEM tasks. Mistral Large 2 provides robust reasoning and multilingual capabilities. Llama 3.1 showcases impressive results across a broad range of benchmarks. Phi-3 models offer remarkable capabilities for their compact size. Amazon Nova models provide cost-effective solutions for specific applications.

The current state of the LLM landscape is characterized by a strong emphasis on enhancing reasoning abilities, expanding multimodal functionalities, improving efficiency and cost-effectiveness, and supporting longer context windows. The rapid pace of innovation ensures that new models with increasingly sophisticated capabilities will continue to emerge. While OpenAI remains a leader in the field, the competitive advantages offered by alternative LLMs underscore the importance of considering specific use case requirements when selecting an LLM. The optimal choice often depends on the particular task, desired performance characteristics, and budgetary constraints, making a thorough understanding of the strengths and limitations of each model crucial for informed decision-making.

## 6\. References

(\#table-of-contents)

1.  OpenAI. (2025, February 27). *Introducing GPT-4.5*. [https://openai.com/index/introducing-gpt-4-5/](https://openai.com/index/introducing-gpt-4-5/)
2.  Anthropic. (2025, February 24). *Claude 3.7 Sonnet and Claude Code*. [https://www.anthropic.com/news/claude-3-7-sonnet](https://www.anthropic.com/news/claude-3-7-sonnet)
3.  Google DeepMind. (n.d.). *Gemini 2.5: Models*. [https://deepmind.google/technologies/gemini/flash-thinking/](https://www.google.com/search?q=https://deepmind.google/technologies/gemini/flash-thinking/)
4.  Exploding Topics. (2025, February). *Top LLMs in February 2025*. [https://explodingtopics.com/blog/list-of-llms](https://explodingtopics.com/blog/list-of-llms)
5.  OpenAI. (2025, April 16). *Introducing o3 and o4-mini*. [https://openai.com/index/introducing-o3-and-o4-mini/](https://openai.com/index/introducing-o3-and-o4-mini/)
6.  OpenAI. (n.d.). *Models*. [https://platform.openai.com/docs/models](https://platform.openai.com/docs/models)
7.  PYMNTS. (2025, April 18). *OpenAI Says Its Latest Models Bring More Capable AI Agents to Business*. [https://www.pymnts.com/artificial-intelligence-2/2025/openai-says-its-latest-models-bring-more-capable-ai-agents-to-business/](https://www.pymnts.com/artificial-intelligence-2/2025/openai-says-its-latest-models-bring-more-capable-ai-agents-to-business/)
8.  Microsoft Azure. (2025, April). *Azure OpenAI Service Models overview*. [https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/models](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/models)
9.  OpenAI. (n.d.). *Model index for the OpenAI API*. [https://model-spec.openai.com/](https://model-spec.openai.com/)
10. OpenAI. (2025, April 14). *GPT-4.1*. [https://openai.com/index/gpt-4-1/](https://openai.com/index/gpt-4-1/)
11. OpenAI. (2025, February 27). *OpenAI GPT-4.5 System Card*. [https://cdn.openai.com/gpt-4-5-system-card-2272025.pdf](https://cdn.openai.com/gpt-4-5-system-card-2272025.pdf)
12. OpenAI. (2024, May 13). *Hello GPT-4o*. [https://openai.com/index/hello-gpt-4o/](https://openai.com/index/hello-gpt-4o/)
13. Amazon Web Services. (2025, April 17). *Benchmarking Amazon Nova and GPT-4o Models with FloTorch*. [https://aws.amazon.com/blogs/machine-learning/benchmarking-amazon-nova-and-gpt-4o-models-with-flotorch/](https://aws.amazon.com/blogs/machine-learning/benchmarking-amazon-nova-and-gpt-4o-models-with-flotorch/)
14. OpenAI. (2024, July 18). *GPT-4o mini: Advancing cost-efficient intelligence*. [https://openai.com/index/gpt-4o-mini-advancing-cost-efficient-intelligence/](https://openai.com/index/gpt-4o-mini-advancing-cost-efficient-intelligence/)
15. Microsoft Azure. (2024, May 14). *OpenAI’s fastest model, GPT-4o mini, is now available on Azure AI*. [https://azure.microsoft.com/en-us/blog/openais-fastest-model-gpt-4o-mini-is-now-available-on-azure-ai/](https://azure.microsoft.com/en-us/blog/openais-fastest-model-gpt-4o-mini-is-now-available-on-azure-ai/)
16. Box AI. (2025, April 15). *First Look: GPT-4.1 Now Available in Box AI Studio*. [https://blog.box.com/first-look-gpt-4\_1-now-available-box-ai-studio](https://blog.box.com/first-look-gpt-4_1-now-available-box-ai-studio)
17. OpenAI. (2025, April 14). *GPT-4.1 Benchmark Performance Compared to Leading Models*. [https://openai.com/index/gpt-4-1/](https://openai.com/index/gpt-4-1/)
18. OpenAI. (2024, May 13). *GPT-4o System Card*. [https://openai.com/index/gpt-4o-system-card/](https://openai.com/index/gpt-4o-system-card/)
19. OpenAI. (2024, August 15). *Updates to GPT-4o in ChatGPT*. [https://help.openai.com/en/articles/9624314-model-release-notes](https://help.openai.com/en/articles/9624314-model-release-notes)
20. OpenAI. (2024, August 6). *Introducing Structured Outputs*. [https://openai.com/blog/function-calling-and-other-api-updates](https://openai.com/blog/function-calling-and-other-api-updates)
21. OpenAI. (2024, December 17). *Introducing our next generation audio models*. [https://openai.com/index/introducing-our-next-generation-audio-models/](https://openai.com/index/introducing-our-next-generation-audio-models/)
22. GeeksforGeeks. (2024, May 14). *GPT-4o: OpenAI’s New Multimodal Model*. [https://www.geeksforgeeks.org/gpt-4o-openais-new-multimodal-model/](https://www.google.com/search?q=https://www.geeksforgeeks.org/gpt-4o-openais-new-multimodal-model/)
23. OpenAI. (2024, May 13). *Introducing GPT-4o and more tools to ChatGPT free users*. [https://openai.com/index/gpt-4o-and-more-tools-to-chatgpt-free/](https://openai.com/index/gpt-4o-and-more-tools-to-chatgpt-free/)
24. Unthread. (2024, May 14). *The 5 Coolest Features of GPT4o*. [https://unthread.io/blog/the-5-coolest-features-of-gpt4o/](https://unthread.io/blog/the-5-coolest-features-of-gpt4o/)
25. IBM. (2024, May 15). *What is GPT-4o? Understanding OpenAI’s Newest Model*. [https://www.ibm.com/think/topics/gpt-4o](https://www.ibm.com/think/topics/gpt-4o)
26. TechTarget. (2024, May). *GPT-4o explained: Everything you need to know*.([https://www.techtarget.com/whatis/feature/GPT-4o-explained-Everything-you-need-to-know](https://www.techtarget.com/whatis/feature/GPT-4o-explained-Everything-you-need-to-know))
27. FloTorch. (2024, December 3). *Benchmarking Amazon Nova and GPT-4o Models with FloTorch*. [https://aws.amazon.com/blogs/machine-learning/benchmarking-amazon-nova-and-gpt-4o-models-with-flotorch/](https://aws.amazon.com/blogs/machine-learning/benchmarking-amazon-nova-and-gpt-4o-models-with-flotorch/)
28. OpenAI. (n.d.). *Changelog*. [https://platform.openai.com/docs/changelog](https://platform.openai.com/docs/changelog)
29. DataCamp. (2025, April 15). *A Guide to GPT-4.1*. [https://www.datacamp.com/blog/gpt-4-1](https://www.datacamp.com/blog/gpt-4-1)
30. OpenAI. (2024, August 6). *Introducing gpt-4o-2024-08-06*. [https://openai.com/blog/gpt-4o-and-other-updates](https://www.google.com/search?q=https://openai.com/blog/gpt-4o-and-other-updates)
31. OpenAI. (2024, September 12). *Introducing OpenAI o1*. [https://openai.com/index/introducing-openai-o1/](https://www.google.com/search?q=https://openai.com/index/introducing-openai-o1/)
32. Wielded. (2024, May 15). *GPT-4o Benchmark: Detailed Comparison with Claude and Gemini*. [https://wielded.com/blog/gpt-4o-benchmark-detailed-comparison-with-claude-and-gemini](https://wielded.com/blog/gpt-4o-benchmark-detailed-comparison-with-claude-and-gemini)
33. Microsoft Azure. (2024, December 18). *Azure OpenAI Service December 2024 updates*. [https://learn.microsoft.com/en-us/azure/ai-services/openai/whats-new](https://learn.microsoft.com/en-us/azure/ai-services/openai/whats-new)
34. OpenAI. (2024, July 18). *GPT-4o mini: Advancing cost-efficient intelligence*. [https://openai.com/index/gpt-4o-mini-advancing-cost-efficient-intelligence/](https://openai.com/index/gpt-4o-mini-advancing-cost-efficient-intelligence/)
35. Leanware. (2025, February 28). *Grok 3 vs GPT Models Comparison*. [https://www.leanware.co/insights/grok-3-vs-gpt-models-comparison](https://www.leanware.co/insights/grok-3-vs-gpt-models-comparison)
36. OpenAI Developer Community. (2025, March 14). *GPT-4.5 is Incredible, but Critical Improvements Needed for Deep User Engagement*. [https://community.openai.com/t/gpt-4-5-is-incredible-but-critical-improvements-needed-for-deep-user-engagement/1143056](https://community.openai.com/t/gpt-4-5-is-incredible-but-critical-improvements-needed-for-deep-user-engagement/1143056)
37. YouTube. (2024, May 14). *GPT-4o: The New OpenAI Model Explained*. [https://www.youtube.com/watch?v=irYyK-CqcVI](https://www.youtube.com/watch?v=irYyK-CqcVI)
38. Daily.dev. (2024, May 14). *OpenAI's GPT-4o: Everything You Need to Know in One Place*. [https://daily.dev/blog/openais-gpt-4o-everything-you-need-to-know-in-one-place](https://daily.dev/blog/openais-gpt-4o-everything-you-need-to-know-in-one-place)
39. Codingscape. (2025, February 28). *Most Powerful LLMs (Large Language Models)*. [https://codingscape.com/blog/most-powerful-llms-large-language-models](https://codingscape.com/blog/most-powerful-llms-large-language-models)
40. GeeksforGeeks. (2024, May 15). *GPT-4o Mini: A Comprehensive Overview*. [https://www.geeksforgeeks.org/deepseek-r1-vs-deepseek-v3/](https://www.geeksforgeeks.org/deepseek-r1-vs-deepseek-v3/)
41. OpenAI API. (n.d.). *GPT-4o*. [https://platform.openai.com/docs/models/gpt-4o](https://platform.openai.com/docs/models/gpt-4o)
42. Artificial Analysis. (2024, November). *Mistral Large 2 (Nov '24): Intelligence, Performance & Price Analysis*. [https://artificialanalysis.ai/models/mistral-large-2](https://artificialanalysis.ai/models/mistral-large-2)
43. OpenAI. (2025, April 16). *Introducing o3 and o4-mini*. [https://openai.com/index/introducing-o3-and-o4-mini/](https://openai.com/index/introducing-o3-and-o4-mini/)
44. OpenAI. (n.d.). *Models*. [https://platform.openai.com/docs/models](https://platform.openai.com/docs/models)
45. Analytics Vidhya. (2025, February 28). *OpenAI GPT-4.5*. [https://www.analyticsvidhya.com/blog/2025/02/openai-gpt-4-5/](https://www.analyticsvidhya.com/blog/2025/02/openai-gpt-4-5/)
46. Artificial Analysis. (2024, November). *GPT-4o (Nov '24): Intelligence, Performance & Price Analysis*. [https://artificialanalysis.ai/models/gpt-4o](https://artificialanalysis.ai/models/gpt-4o)
47. ZDNet. (2025, April 16). *OpenAI just dropped new o3 and o4-mini reasoning AI models and a surprise agent*. [https://www.zdnet.com/article/openai-just-dropped-new-o3-and-o4-mini-reasoning-ai-models-and-a-surprise-agent/](https://www.zdnet.com/article/openai-just-dropped-new-o3-and-o4-mini-reasoning-ai-models-and-a-surprise-agent/)
48. OpenAI API. (n.d.). *GPT-4o mini*. [https://platform.openai.com/docs/models](https://platform.openai.com/docs/models)
49. Reddit. (n.d.). *Claude 3.7 Sonnet's results on six independent benchmarks : ClaudeAI*. [https://www.reddit.com/r/ClaudeAI/comments/1iz3umm/claude\_37\_sonnets\_results\_on\_six\_independent/](https://www.reddit.com/r/ClaudeAI/comments/1iz3umm/claude_37_sonnets_results_on_six_independent/)
50. Microsoft Azure. (2024, December 17). *Azure OpenAI Service December 2024 updates*. [https://learn.microsoft.com/en-us/azure/ai-services/openai/whats-new](https://learn.microsoft.com/en-us/azure/ai-services/openai/whats-new)
51. OpenAI. (2025, April 16). *Introducing o3 and o4-mini*. [https://openai.com/index/introducing-o3-and-o4-mini/](https://openai.com/index/introducing-o3-and-o4-mini/)
52. Intento. (2024, May 14). *May 2024: Integrations with LLMs from Anthropic, Google, and OpenAI, and more\!*. [https://inten.to/blog/may-2024-integrations-with-llms-from-anthropic-google-and-openai-and-more/](https://inten.to/blog/may-2024-integrations-with-llms-from-anthropic-google-and-openai-and-more/)
53. xAI. (2025, February 17). *Grok 3 Beta — The Age of Reasoning Agents*. [https://x.ai/news/grok-3](https://x.ai/news/grok-3)
54. xAI. (2025, February 17). *Grok 3 Beta — The Age of Reasoning Agents*. [https://x.ai/news/grok-3](https://x.ai/news/grok-3)
55. BentoML. (2025, March 27). *The Complete Guide to DeepSeek Models: From V3 to R1 and Beyond*. [https://www.bentoml.com/blog/the-complete-guide-to-deepseek-models-from-v3-to-r1-and-beyond](https://www.bentoml.com/blog/the-complete-guide-to-deepseek-models-from-v3-to-r1-and-beyond)
56. DataCamp. (2024, December 6). *OpenAI o1: A New Era of Reasoning in AI*. [https://www.datacamp.com/blog/open-ai-o1](https://www.datacamp.com/blog/open-ai-o1)
57. Reddit. (n.d.). *the latest gpt-4o seems to be worse in some benchmarks. : singularity*. [https://www.reddit.com/r/singularity/comments/1gwaa1c/the\_latest\_gpt4o\_seems\_to\_be\_worse\_in\_some/](https://www.reddit.com/r/singularity/comments/1gwaa1c/the_latest_gpt4o_seems_to_be_worse_in_some/)
58. OpenAI. (2024, September 12). *Introducing OpenAI o1-mini: Advancing cost-efficient reasoning*. [https://openai.com/index/openai-o1-mini-advancing-cost-efficient-reasoning/](https://openai.com/index/openai-o1-mini-advancing-cost-efficient-reasoning/)
59. InfoQ. (2025, February 7). *Google Expands Gemini 2 Family with Flash-Lite and Pro Models*. [https://www.infoq.com/news/2025/02/gemini-2-flash-lite-pro-models/](https://www.infoq.com/news/2025/02/gemini-2-flash-lite-pro-models/)
60. OpenAI API. (n.d.). *o1-mini*. [https://platform.openai.com/docs/models](https://platform.openai.com/docs/models)
61. Zapier. (2025, February 28). *The best LLMs in 2025*. [https://zapier.com/blog/best-llm/](https://zapier.com/blog/best-llm/)
62. DataOps Labs. (2025, March 28). *DeepSeek R1 vs DeepSeek V3*. [https://blog.dataopslabs.com/deepseek-r1-vs-deepseek-v3](https://blog.dataopslabs.com/deepseek-r1-vs-deepseek-v3)
63. Spheron. (2024, April 15). *Llama 3.1 In-Depth Analysis: Cutting Through the Noise*. [https://blog.spheron.network/llama-31-in-depth-analysis-cutting-through-the-noise](https://blog.spheron.network/llama-31-in-depth-analysis-cutting-through-the-noise)
64. DocsBot AI. (n.d.). *Compare DeepSeek-R1 vs DeepSeek-V3*. [https://docsbot.ai/models/compare/deepseek-r1/deepseek-v3](https://docsbot.ai/models/compare/deepseek-r1/deepseek-v3)
65. xAI. (2025, February 17). *Grok-3*. [https://x.ai/news/grok-3](https://x.ai/news/grok-3)
66. Reddit. (n.d.). *Gemini 2.0 Flash vs 1.5 Pro vs 2.0 Flash-Lite for coding? : Bard*.([https://www.reddit.com/r/Bard/comments/1j6ai3s/gemini\_20\_flash\_vs\_15\_pro\_vs\_20\_flashlite\_for/](https://www.reddit.com/r/Bard/comments/1j6ai3s/gemini_20_flash_vs_15_pro_vs_20_flashlite_for/))
67. OpenAI. (2025, January 31). *Introducing OpenAI o3-mini*. [https://openai.com/index/openai-o3-mini/](https://openai.com/index/openai-o3-mini/)
68. OpenAI. (2025, April 16). *Introducing o3 and o4-mini*. [https://openai.com/index/introducing-o3-and-o4-mini/](https://openai.com/index/introducing-o3-and-o4-mini/)
69. Gaper. (2024, July 23). *Meta’s New Llama 3.1*. [https://gaper.io/metas-new-llama-3-1/](https://gaper.io/metas-new-llama-3-1/)
70. Hydrox AI. (2024, September 13). *Evaluating OpenAI's o1-mini and GPT-4o mini - Advances and Areas for Improvement*. [https://www.hydrox.ai/blogs/evaluating-openais-o1-mini-and-gpt-4o-mini---advances-and-areas-for-improvement](https://www.hydrox.ai/blogs/evaluating-openais-o1-mini-and-gpt-4o-mini---advances-and-areas-for-improvement)
71. Reddit. (n.d.). *GPT-4.5 Benchmark Performance : singularity*. [https://www.reddit.com/r/singularity/comments/1izp75f/gpt45\_benchmark\_performance/](https://www.reddit.com/r/singularity/comments/1izp75f/gpt45_benchmark_performance/)
72. OpenAI. (n.d.). *OpenAI*. [https://openai.com/](https://openai.com/)
73. OpenAI. (n.d.). *o1*. [https://openai.com/o1/](https://openai.com/o1/)
74. DocsBot AI. (n.d.). *Compare DeepSeek-V3 vs DeepSeek-R1*. [https://docsbot.ai/models/compare/deepseek-v3/deepseek-r1](https://docsbot.ai/models/compare/deepseek-v3/deepseek-r1)
75. MakeUseOf. (2025, April 15). *What You Can Do With GPT-4.1*. [https://www.makeuseof.com/what-you-can-do-with-gpt-4-1/](https://www.makeuseof.com/what-you-can-do-with-gpt-4-1/)
76. OpenAI API. (n.d.). *o1*. [https://platform.openai.com/docs/models](https://platform.openai.com/docs/models)
77. Bardeen AI. (n.d.). *DeepSeek R1 vs V3*. [https://www.bardeen.ai/answers/deepseek-r1-vs-v3](https://www.bardeen.ai/answers/deepseek-r1-vs-v3)
78. Wikipedia. (2024, May 16). *GPT-4o*.(https://en.wikipedia.org/wiki/GPT-4o)
79. OpenAI API. (n.d.). *o1-mini*. [https://platform.openai.com/docs/models](https://platform.openai.com/docs/models)
80. Kili Technology. (2024, July 25). *A Guide to GPT4o Mini: OpenAI's Smaller, More Efficient Language Model*. [https://kili-technology.com/large-language-models-llms/a-guide-to-gpt4o-mini-openai-s-smaller-more-efficient-language-model](https://kili-technology.com/large-language-models-llms/a-guide-to-gpt4o-mini-openai-s-smaller-more-efficient-language-model)
81. Mistral AI. (n.d.). *Benchmarks*. [https://docs.mistral.ai/getting-started/models/benchmark/](https://docs.mistral.ai/getting-started/models/benchmark/)
82. OpenAI. (2025, April 16). *Introducing o3 and o4-mini*. [https://openai.com/index/introducing-o3-and-o4-mini/](https://openai.com/index/introducing-o3-and-o4-mini/)
83. Microsoft Azure. (n.d.). *Azure OpenAI Service Models overview*. [https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/models](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/models)
84. Reddit. (n.d.). *GPT4.5 is here, but is it really an upgrade? My initial thoughts and comparisons to 4o : ChatGPTPro*.([https://www.reddit.com/r/ChatGPTPro/comments/1j55h6m/gpt45\_is\_here\_but\_is\_it\_really\_an\_upgrade\_my/](https://www.reddit.com/r/ChatGPTPro/comments/1j55h6m/gpt45_is_here_but_is_it_really_an_upgrade_my/))
85. OpenAI. (2024, May 13). *GPT-4o System Card*. [https://openai.com/index/gpt-4o-system-card/](https://openai.com/index/gpt-4o-system-card/)
86. OpenAI API. (n.d.). *o3-mini*. [https://platform.openai.com/docs/models](https://platform.openai.com/docs/models)
87. Microsoft Azure. (n.d.). *Azure OpenAI Service Models overview*. [https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/models](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/models)
88. OpenAI. (2025, April 16). *o3 and o4-mini System Card*. [https://cdn.openai.com/pdf/2221c875-02dc-4789-800b-e7758f3722c1/o3-and-o4-mini-system-card.pdf](https://cdn.openai.com/pdf/2221c875-02dc-4789-800b-e7758f3722c1/o3-and-o4-mini-system-card.pdf)
89. WandB. (2025, February 27). *Evaluating Claude 3.7 Sonnet Performance: reasoning and cost optimization*.(https://wandb.ai/byyoung3/Generative-AI/reports/Evaluating-Claude-3-7-Sonnet-Performance-reasoning-and-cost-optimization--VmlldzoxMTYzNDEzNQ)
90. Reddit. (n.d.). *Claude 3.7 benchmarks : ClaudeAI*. [https://www.reddit.com/r/ClaudeAI/comments/1ix9bou/claude\_37\_benchmarks/](https://www.google.com/search?q=https://www.reddit.com/r/ClaudeAI/comments/1ix9bou/claude_37_benchmarks/)
91. FutureSkills Academy. (2025, February 1). *OpenAI o3-mini: A Cost-Effective Reasoning Model*. [https://futureskillsacademy.com/blog/openai-o3-mini/](https://futureskillsacademy.com/blog/openai-o3-mini/)
92. OpenAI. (2025, April 16). *Thinking with images*. [https://openai.com/index/thinking-with-images/](https://openai.com/index/thinking-with-images/)
93. DataCamp. (2025, February 28). *Claude 3.7 Sonnet: Anthropic's Latest Model*. [https://www.datacamp.com/blog/claude-3-7-sonnet](https://www.datacamp.com/blog/claude-3-7-sonnet)
94. DocsBot AI. (n.d.). *Compare Mistral Large 2 vs GPT-4 32K*. [https://docsbot.ai/models/compare/mistral-large-2/gpt-4-32k](https://docsbot.ai/models/compare/mistral-large-2/gpt-4-32k)
95. Exploding Topics. (2025, March 13). *List of LLMs*. [https://explodingtopics.com/blog/list-of-llms](https://explodingtopics.com/blog/list-of-llms)
96. Reddit. (n.d.). *Gemini 2.0 Flash vs 1.5 Pro vs 2.0 Flash-Lite for coding? : Bard*.(https://www.reddit.com/r/Bard/comments/1j6ai3s/gemini\_20\_flash\_vs\_15\_pro\_vs\_20\_flashlite\_for/)
97. NIST. (2024, December 12). *Pre-Deployment Evaluation of OpenAI’s o1 Model*. [https://www.nist.gov/news-events/news/2024/12/pre-deployment-evaluation-openais-o1-model](https://www.nist.gov/news-events/news/2024/12/pre-deployment-evaluation-openais-o1-model)
98. Exploding Topics. (2025, March 13). *List of LLMs*. [https://explodingtopics.com/blog/list-of-llms](https://explodingtopics.com/blog/list-of-llms)
99. Microsoft Tech Community. (2025, April 15). *Discover the new multi-lingual high-quality Phi-3.5 SLMs*. [https://techcommunity.microsoft.com/blog/azure-ai-services-blog/discover-the-new-multi-lingual-high-quality-phi-3-5-slms/4225280](https://techcommunity.microsoft.com/blog/azure-ai-services-blog/discover-the-new-multi-lingual-high-quality-phi-3-5-slms/4225280)
100. OpenCV. (2025, February 18). *Grok-3: A New Era of AI Performance*. [https://opencv.org/blog/grok-3/](https://opencv.org/blog/grok-3/)
101. Reddit. (n.d.). *Rumoured GPT-4 Architecture (Simplified) : LocalLLaMA*. [https://www.reddit.com/r/LocalLLaMA/comments/1c1en6n/rumoured\_gpt4\_architecture\_simplified/](https://www.reddit.com/r/LocalLLaMA/comments/1c1en6n/rumoured_gpt4_architecture_simplified/)
102. OpenAI. (2024, September 12). *OpenAI o1 System Card*. [https://openai.com/index/openai-o1-system-card/](https://openai.com/index/openai-o1-system-card/)
103. Willison, S. (2025, April 14). *GPT-4.1: Three new million token input models from OpenAI, including their cheapest model yet*. [https://simonwillison.net/2025/Apr/14/gpt-4-1/](https://simonwillison.net/2025/Apr/14/gpt-4-1/)
104. MyScale. (2024, April 15). *Llama 3.1 405B, 70B, 8B: A Quick Comparison*. [https://myscale.com/blog/llama-3-1-405b-70b-8b-quick-comparison/](https://myscale.com/blog/llama-3-1-405b-70b-8b-quick-comparison/)
105. Techxmedia. (2025, April 15). *OpenAI Introduces GPT-4.1 With Major Performance Upgrades*. [https://techxmedia.com/en/openai-introduces-gpt-4-1-with-major-performance-upgrades/](https://techxmedia.com/en/openai-introduces-gpt-4-1-with-major-performance-upgrades/)
106. DocsBot AI. (n.d.). *Compare Mistral Large vs Mistral Large 2*. [https://docsbot.ai/models/compare/mistral-large/mistral-large-2](https://docsbot.ai/models/compare/mistral-large/mistral-large-2)
107. Microsoft Azure. (2024, May 14). *OpenAI’s fastest model, GPT-4o mini, is now available on Azure AI*. [https://azure.microsoft.com/en-us/blog/openais-fastest-model-gpt-4o-mini-is-now-available-on-azure-ai/](https://www.google.com/search?q=https://azure.microsoft.com/en-us/azure/ai-services/openai/whats-new)
108. Microsoft Research. (2024, August 30). *Phi-3 Technical Report: A Highly Capable Language Model Locally on Your Phone*. [https://arxiv.org/pdf/2404.14219](https://www.google.com/search?q=https://arxiv.org/pdf/2404.14219)
109. OpenAI. (2024, July 18). *GPT-4o mini: Advancing cost-efficient intelligence*. [https://openai.com/index/gpt-4o-mini-advancing-cost-efficient-intelligence/](https://openai.com/index/gpt-4o-mini-advancing-cost-efficient-intelligence/)
110. Helicone. (2025, February 18). *Grok 3 Benchmark Comparison: How Does It Stack Up?*. [https://www.helicone.ai/blog/grok-3-benchmark-comparison](https://www.helicone.ai/blog/grok-3-benchmark-comparison)
111. DocsBot AI. (n.d.). *OpenAI's GPT-4.5: Most Powerful AI Model Yet*. [https://docsbot.ai/article/openais-gpt-4-5-most-powerful-ai-model-yet](https://docsbot.ai/article/openais-gpt-4-5-most-powerful-ai-model-yet)
112. Microsoft Research. (2024, August 30). *Phi-3 Technical Report: A Highly Capable Language Model Locally on Your Phone*. [https://arxiv.org/html/2404.14219v3](https://arxiv.org/html/2404.14219v3)
113. Wikipedia. (2025, April 18). *OpenAI o3*. [https://en.wikipedia.org/wiki/OpenAI\_o3](https://en.wikipedia.org/wiki/OpenAI_o3)
114. TechTarget. (n.d.). *GPT-4o explained: Everything you need to know*.([https://www.techtarget.com/whatis/feature/GPT-4o-explained-Everything-you-need-to-know\#:\~:text=The%20multimodal%20capabilities%20of%20GPT,Data%20analysis](https://www.google.com/search?q=https://www.techtarget.com/whatis/feature/GPT-4o-explained-Everything-you-need-to-know%23:~:text%3DThe%2520multimodal%2520capabilities%2520of%2520GPT,Data%2520analysis).)
115. Google Developers Blog. (2025, April 9). *Start building with the Gemini 2.0 Flash family*. [https://developers.googleblog.com/en/start-building-with-the-gemini-2-0-flash-family/](https://developers.googleblog.com/en/start-building-with-the-gemini-2-0-flash-family/)
116. Reddit. (n.d.). *GPT4o Features Summary : singularity*. [https://www.reddit.com/r/singularity/comments/1cr7tvm/gpt4o\_features\_summary/](https://www.reddit.com/r/singularity/comments/1cr7tvm/gpt4o_features_summary/)
117. OpenAI Help Center. (n.d.). *How can I access GPT-4, GPT-4o, and GPT-4o mini?*. [https://help.openai.com/en/articles/7102672-how-can-i-access-gpt-4-gpt-4o-and-gpt-4o-mini](https://help.openai.com/en/articles/7102672-how-can-i-access-gpt-4-gpt-4o-and-gpt-4o-mini)
118. Anthropic. (2025, February 24). *Claude 3.7 Sonnet*. [https://www.anthropic.com/news/claude-3-7-sonnet](https://www.anthropic.com/news/claude-3-7-sonnet)
119. OpenAI. (2024, September 12). *Introducing OpenAI o1-mini: Advancing cost-efficient reasoning*. [https://openai.com/index/openai-o1-mini-advancing-cost-efficient-reasoning/](https://openai.com/index/openai-o1-mini-advancing-cost-efficient-reasoning/)
120. Unthread. (2024, May 14). *The 5 Coolest Features of GPT4o*. [https://unthread.io/blog/the-5-coolest-features-of-gpt4o/](https://unthread.io/blog/the-5-coolest-features-of-gpt4o/)
121. ManageEngine. (2024, September 20). *OpenAI's o1: One small step for man, one giant leap for mankind?*. [https://insights.manageengine.com/artificial-intelligence/openai-o1/](https://insights.manageengine.com/artificial-intelligence/openai-o1/)
122. Google Developers Blog. (2025, April 16). *Gemini 2.0 Family expands for developers*. [https://developers.googleblog.com/en/gemini-2-family-expands/](https://developers.googleblog.com/en/gemini-2-family-expands/)
123. OpenAI. (2025, April 16). *o3 and o4-mini System Card*. [https://cdn.openai.com/pdf/2221c875-02dc-4789-800b-e7758f3722c1/o3-and-o4-mini-system-card.pdf](https://cdn.openai.com/pdf/2221c875-02dc-4789-800b-e7758f3722c1/o3-and-o4-mini-system-card.pdf)
124. PYMNTS. (2025, April 18). *OpenAI Says Its Latest Models Bring More Capable AI Agents to Business*. [https://www.pymnts.com/artificial-intelligence-2/2025/openai-says-its-latest-models-bring-more-capable-ai-agents-to-business/](https://www.pymnts.com/artificial-intelligence-2/2025/openai-says-its-latest-models-bring-more-capable-ai-agents-to-business/)
125. Acorn. (n.d.). *OpenAI*. [https://www.acorn.io/resources/learning-center/openai/](https://www.acorn.io/resources/learning-center/openai/)
126. OpenAI. (2024, May 13). *Introducing GPT-4o and more tools to ChatGPT free users*. [https://openai.com/index/gpt-4o-and-more-tools-to-chatgpt-free/](https://openai.com/index/gpt-4o-and-more-tools-to-chatgpt-free/)
127. Tomsguide. (2025, April 12). *OpenAI is retiring GPT-4 from ChatGPT—here's what that means for you*. [https://www.tomsguide.com/ai/chatgpt/openai-is-retiring-gpt-4-from-chatgpt-heres-what-that-means-for-you](https://www.tomsguide.com/ai/chatgpt/openai-is-retiring-gpt-4-from-chatgpt-heres-what-that-means-for-you)
128. OpenAI Developer Community. (2024, May 29). *OpenAI has begun training its next frontier model*. [https://community.openai.com/t/openai-has-begun-training-its-next-frontier-model/784085](https://community.openai.com/t/openai-has-begun-training-its-next-frontier-model/784085)
129. Vellum AI. (2024, September 21). *Analysis: OpenAI o1 vs GPT-4o*. [https://www.vellum.ai/blog/analysis-openai-o1-vs-gpt-4o](https://www.vellum.ai/blog/analysis-openai-o1-vs-gpt-4o)
130. IBM. (2024, May 15). *What is GPT-4o? Understanding OpenAI’s Newest Model*. [https://www.ibm.com/think/topics/gpt-4o](https://www.ibm.com/think/topics/gpt-4o)
131. Vellum AI. (2024, April 15). *Llama 3.3 70b vs GPT-4o*. [https://www.vellum.ai/blog/llama-3-3-70b-vs-gpt-4o](https://www.vellum.ai/blog/llama-3-3-70b-vs-gpt-4o)
132. MeetCody AI. (2024, September 13). *OpenAI o1 Pricing & Performance Comparison*. [https://meetcody.ai/blog/openai-o1-pricing-performance-comparison/](https://meetcody.ai/blog/openai-o1-pricing-performance-comparison/)
133. Section School. (2024, May 14). *What is GPT4o?*. [https://www.sectionschool.com/blog/what-is-gpt4o](https://www.sectionschool.com/blog/what-is-gpt4o)
134. Botpress. (2025, April 15). *Everything you should know about GPT-5*. [https://botpress.com/blog/everything-you-should-know-about-gpt-5](https://botpress.com/blog/everything-you-should-know-about-gpt-5)
135. DataCamp. (2024, May 14). *What is GPT-4o?*. [https://www.datacamp.com/blog/what-is-gpt-4o](https://www.datacamp.com/blog/what-is-gpt-4o)
136. Reddit. (n.d.). *Ok o3 and o4 mini are here and they really has tool use : ChatGPT*.([https://www.reddit.com/r/ChatGPT/comments/1k0pway/ok\_o3\_and\_o4\_mini\_are\_here\_and\_they\_really\_has/](https://www.google.com/search?q=https://www.reddit.com/r/ChatGPT/comments/1k0pway/ok_o3_and_o4_mini_are_here_and_they_really_has/))
137. Reddit. (n.d.). *GPT4.5 Benchmark Performance : singularity*. [https://www.reddit.com/r/singularity/comments/1izp75f/gpt45\_benchmark\_performance/](https://www.reddit.com/r/singularity/comments/1izp75f/gpt45_benchmark_performance/)
138. Arize AI. (2024, September 13). *Exploring OpenAI o1-preview and o1-mini*. [https://arize.com/blog/exploring-openai-o1-preview-and-o1-mini/](https://arize.com/blog/exploring-openai-o1-preview-and-o1-mini/)
