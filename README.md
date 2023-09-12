# low-cost-program-of-thought
Experimentation with code-generative models using program-of-thought training for low-cost use cases

SPRING 2023 

This project was created as an end-of-term project for CS 224U: Natural Language Understanding in the Spring of 2023 and continued as ongoing research. Shared code repo for pair-programming work included: https://github.com/jjyang12/cs224u

# Hypothesis 
We hypothesize that we can produce and improve a low-cost model to serve as a replacement to Codexin the PoT framework. We define a low-cost model to be one that is either publicly available at no cost or one that is available for subscription use at a reduced rate to OpenAI products. While the low-cost model (we ultimately focus on Cohere’s Command Nightly model) may not be as proficient as Codex at valid code generation, we plan to use error analysis, self-debugging, self-consistency, and post-processing to directly target issues native to
the low-cost model and improve its ability to produce correct results in a PoT framework. Specifically, our goal for improvement will be to target at least one common type of failure with the lowcost model (i.e. Syntax errors, Logic generation errors, etc) and to show that in combination with techniques above we can achieve a greater accuracy and/or qualitative result than the low-cost model alone.

Topics covered and tools used: 
- Program of Thought Prompting
- Chain of Thought Prompting
- Temperature Experimentation
- Few-Shot Responses
- Orchestration Models
- LLMs
- Codex / GPT-3
- Cohere Command Nightly
- Code Parrot
- Post-Processing
- Self-Debugging
- Ensemble Models
