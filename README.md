<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:043361,100:337ab7&height=180&section=header&text=Alessandro%20Giagnorio&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=PhD%20Researcher%20%40%20USI%20%C2%B7%20AI4SE%20%C2%B7%20Code%20Generation%20%C2%B7%20LLM%20Benchmarks&descAlignY=58&descSize=18" width="100%" alt="Alessandro Giagnorio"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1200&color=2C5364&center=true&vCenter=true&width=650&lines=Improving+and+evaluating+LLMs+for+code+generation;LLMs+%C3%97+code+generation+%C3%97+uncommon+programming+languages" alt="typing-svg"/>

<br/>

[![Website](https://img.shields.io/badge/Website-0f2027?style=for-the-badge&logo=googlechrome&logoColor=white)](https://devy99.github.io/) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alessandro-giagnorio/) [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=maildotru&logoColor=white)](mailto:giagna@usi.ch) [![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?hl=en&user=0EiteC8AAAAJ)

![Open to Internships](https://img.shields.io/badge/Open_to-Research_Internships-1a7f37?style=for-the-badge)

</div>

<br/>

## 👋 About
I am a PhD student at Università della Svizzera italiana (USI), working in the [SEART](https://seart.si.usi.ch/) group under the supervision of Prof. [Gabriele Bavota](https://www.inf.usi.ch/faculty/bavota/). My research aims to improve LLMs for software engineering tasks, with a particular focus on automating code generation and completion.

In particular, my research interests include:
- personalizing small models for developer- and organization-specific codebases
- enhancing LLMs for uncommon, new, and niche programming languages
- improving the quality and reliability of code generation benchmarks
- understanding how different types of information affect the performance of AI coding agents

Over the course of my PhD, I have released open-source datasets, benchmarks, and models, which are available on my [🤗 Hugging Face profile](https://huggingface.co/Devy1).

<br/>

## 📚 Publications

<table>

<tr>
<td width="100%">

**[No Resource, No Benchmarks, No Problem? Evaluating and Improving LLMs for Code Generation in No-Resource Languages](https://doi.org/10.1109/TSE.2026.3703553)**
<br/>
**Alessandro Giagnorio**, Alberto Martin-Lopez, Gabriele Bavota
<br/>

[![DOI](https://img.shields.io/badge/DOI-10.1109%2FTSE.2026.3703553-blue?style=plastic)](https://doi.org/10.1109%2FTSE.2026.3703553)[![Code](https://img.shields.io/badge/Code-181717?style=plastic&logo=github&logoColor=white)](https://github.com/Devy99/no-resource-pl-study) [![Dataset](https://img.shields.io/badge/🤗_Benchmarks-FFD21E?style=plastic)](https://huggingface.co/collections/Devy1/no-resource-benchmarks)

📙 *IEEE Transactions on Software Engineering (TSE)*

Investigated how LLMs can be taught to generate code for no-resource programming languages. Introduced new code generation benchmarks and evaluated pre-training, fine-tuning, and retrieval-augmented approaches. Proposed *fine-tuning reuse* to significantly improve model performance at a fraction of the computational cost.

</td>
</tr>



<tr>
<td width="100%">

**[Teaching LLMs a Low-Resource Language: Enhancing Code Completion in Pharo](https://arxiv.org/abs/2607.04939)**
<br/>
**Kilian Kier**, **Alessandro Giagnorio**, **Omar AbedelKader**, Oleksandr Zaitsev, Robert Peharz, Romain Robbes, Gabriele Bavota, Stéphane Ducasse
<br/>

[![arXiv](https://img.shields.io/badge/arXiv-2607.04939-b31b1b?style=flat-square&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2607.04939)[![Code](https://img.shields.io/badge/Code-181717?style=plastic&logo=github&logoColor=white)](https://github.com/kilian-kier/pharo-llm-completion) [![Dataset](https://img.shields.io/badge/🤗_Models_and_Benchmarks-FFD21E?style=plastic)](https://huggingface.co/collections/Devy1/llms-specialized-in-pharo)

🏛️ *42nd IEEE International Conference on Software Maintenance and Evolution (ICSME 2026)* 

Researched techniques for improving code completion in the Pharo programming language. Released a family of specialized small language models that outperformed models up to ~320x larger on Pharo code completion, together with a toolkit including language-specific datasets, benchmarks, parsers, and evaluation infrastructure.

</td>
</tr>



<tr>
<td width="100%">

**[Evaluating the Impact of Post-Training Quantization on Large Language Models for Code Generation](https://doi.org/10.1145/3794763.3794810)**
<br/>
**Alessandro Giagnorio**, Antonio Mastropaolo, Saima Afrin, Massimiliano Di Penta, Gabriele Bavota
<br/>

[![DOI](https://img.shields.io/badge/DOI-10.1145/3794763.3794810-blue?style=plastic)](https://doi.org/10.1145/3794763.3794810) [![Code](https://img.shields.io/badge/Code-181717?style=plastic&logo=github&logoColor=white)](https://github.com/Devy99/quantization-study) [![Models](https://img.shields.io/badge/🤗_Quantized_Models-FFD21E?style=plastic)](https://huggingface.co/collections/Devy1/quantization-for-code-generation)

🏛️ *34th IEEE/ACM International Conference on Program Comprehension (ICPC 2026)* 

Studied post-training quantization for code LLMs. Evaluated memory-performance trade-offs across multiple quantization levels. Demonstrated that 4-bit precision reduces memory usage by 70% without significant performance loss, while targeted calibration strategies mitigate accuracy degradation at extreme compression levels.

</td>
</tr>



<tr>
<td width="100%">

**[Guidelines to Prompt Large Language Models for Code Generation: An Empirical Characterization](https://doi.org/10.1145/3794763.3794819)**
<br/>
**Alessandro Midolo**, **Alessandro Giagnorio**, Fiorella Zampetti, Rosalia Tufano, Gabriele Bavota, Massimiliano Di Penta
<br/>

[![DOI](https://img.shields.io/badge/DOI-10.1145/3794763.3794819-blue?style=plastic)](https://doi.org/10.1145/3794763.3794819) [![Artifact](https://img.shields.io/badge/Artifact-181717?style=plastic&logo=zenodo&logoColor=white)](https://zenodo.org/records/17456075) 

🏛️ *34th IEEE/ACM International Conference on Program Comprehension (ICPC 2026)* 

Designed an iterative, test-driven pipeline to optimize prompts for LLM-based code generation and improve output accuracy. Derived a comprehensive set of guidelines to help developers and researchers write more effective prompts for code generation tasks. 

</td>
</tr>



<tr>
<td width="100%">

**[Enhancing Code Generation for Low-Resource Languages: No Silver Bullet](https://doi.org/10.1109/ICPC66645.2025.00058)**
<br/>
**Alessandro Giagnorio**, Alberto Martin-Lopez, Gabriele Bavota
<br/>

[![DOI](https://img.shields.io/badge/DOI-10.1109%2FICPC66645.2025.00058-blue?style=plastic)](https://doi.org/10.1109%2FICPC66645.2025.00058) [![Code](https://img.shields.io/badge/Code-181717?style=plastic&logo=github&logoColor=white)](https://github.com/Devy99/low-resource-study) 

🏛️ *33rd IEEE/ACM International Conference on Program Comprehension (ICPC 2025)*

Investigated the performance of Large Language Models for code generation on low-resource programming languages. Proposed and evaluated several prompting and training techniques on R and Racket, demonstrating that fine-tuning significantly improves smaller models, while in-context learning is most effective for larger models

</td>
</tr>




<tr>
<td width="100%">

**[Why Personalizing Deep Learning-Based Code Completion Tools Matters](https://doi.org/10.1145/3725732)**
<br/>
**Alessandro Giagnorio**, Alberto Martin-Lopez, Gabriele Bavota
<br/>

[![DOI](https://img.shields.io/badge/DOI-10.1145%2F3725732-blue?style=plastic)](https://doi.org/10.1145%2F3725732) [![Code](https://img.shields.io/badge/Code-181717?style=plastic&logo=github&logoColor=white)](https://github.com/Devy99/comp-personalization) 

📙 *ACM Transactions on Software Engineering and Methodology (TOSEM)*

Conducted a large-scale empirical study on personalization strategies for deep learning-based code completion. Designed and executed experiments to train and evaluate _developer-_ and _organization-specific_ models across 136 developers and two software ecosystems. Demonstrated that organization-specific fine-tuning matches the performance of ~10x larger generic models, significantly reducing GPU inference and deployment costs.

</td>
</tr>


</table>

<br/>

## 🛠️ Research & Technical Toolkit

<div align="center">

**Languages, Libraries and Tools**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square)

![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square) ![Tree-sitter](https://img.shields.io/badge/Tree--sitter-6A9FB5?style=flat-square) ![LiteLLM](https://img.shields.io/badge/LiteLLM-000000?style=flat-square) ![vLLM](https://img.shields.io/badge/vLLM-4B56D2?style=flat-square)

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square) ![Slurm](https://img.shields.io/badge/Slurm-555555?style=flat-square)


**Research Expertise**

![Code LLMs and Agents](https://img.shields.io/badge/Code_LLMs_and_Agents-1F6FEB?style=flat-square) ![Model Training](https://img.shields.io/badge/Model_Training-5A29E4?style=flat-square) ![Benchmark Evaluation](https://img.shields.io/badge/Benchmark_Evaluation-0969DA?style=flat-square) ![Empirical Evaluation](https://img.shields.io/badge/Empirical_Evaluation-8250DF?style=flat-square)

![Software Analytics](https://img.shields.io/badge/Software_Analytics-6F42C1?style=flat-square) ![Reproducible Research](https://img.shields.io/badge/Reproducible_Research-1A7F37?style=flat-square) ![Statistical Analysis](https://img.shields.io/badge/Statistical_Analysis-B31B1B?style=flat-square) 

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:337ab7,100:043361&height=100&section=footer" width="100%"/>

</div>
