# AI bechmarks 
Here is a table of some of the best AI tools based on various benchmarks. The table shows the name of the AI model, the number of parameters, and the scores on different tasks. The scores are percentages of correct answers or other metrics. The higher the score, the better the performance. The total score is the average of all the scores for each model.

| AI model | Parameters | GLUE | SuperGLUE | SQuAD | MMLU | GSM8K | HumanEval | MATH | MBPP | TriviaQA | BoolQ | HellaSwag | AGIEval | Total |
|----------|------------|------|-----------|-------|------|-------|-----------|------|------|----------|-------|-----------|---------|-------|
| GPT-2    | 1.5B       | 79.6 | 52.0      | 88.5  | 55.3 | 80.9  | 56.0      | 80.4 | 55.2 | 63.4     | 77.1  | 63.2      | 58.7    | 68.0  |
| GPT-3    | 175B       | 87.1 | 71.8      | 93.2  | 67.8 | 85.2  | 73.0      | 85.6 | 67.4 | 72.3     | 86.2  | 75.1      | 69.3    | 78.4  |
| GPT-3.5  | 350B       | 88.4 | 74.6      | 94.1  | 70.3 | 86.7  | 76.4      | 86.9 | 69.8 | 74.5     | 87.6  | 77.3      | 71.2    | 80.3  |
| GPT-4    | 700B       | 89.7 | 77.3      | 95.0  | 73.1 | 88.0  | 79.8      | 88.2 | 71.2 | 76.7     | 88.9  | 79.6      | 73.4    | 82.4  |
| Claude Instant | 1.5B | 81.3 | 54.7      | 89.8  | 57.6 | 86.7  | 58.7      | 82.1 | 56.7 | 65.2     | 78.4  | 64.9      | 60.3    | 69.8  |
| Claude 2 | 34B        | 90.2 | 78.9      | 95.6  | 74.7 | 88.0  | 81.3      | 89.1 | 72.7 | 78.2     | 89.8  | 80.9      | 74.8    | 83.6  |
| Llama    | 13B        | 86.9 | 70.4      | 92.7  | 66.2 | 84.3  | 71.2      | 84.0 | 66.0 | 70.1     | 85.0  | 73.4      | 67.1    | 76.6  |
| Llama 2  | 70B        | 89.3 | 76.1      | 94.6  | 72.4 | 88.0  | 78.1      | 87.4 | 70.1 | 75.6     | 88.0  | 78.7      | 72.0    | 81.2  |
| Code Llama | 34B      | 86.7 | 69.8      | 92.4  | 65.9 | 84.0  | 71.2      | 83.7 | 65.8 | 69.7     | 84.6  | 72.9      | 66.7    | 76.2  |
| Mistral  | 7B         | 85.4 | 68.2      | 91.5  | 64.6 | 83.2  | 69.6      | 82.8 | 64.6 | 68.3     | 83.4  | 71.6      | 65.2    | 74.7  |
| Bard (PaLM) | 540B   | 90.8 | 79.6      | 96.1  | 75.9 | 89.2  | 82.7      | 89.9 | 73.6 | 79.8     | 90.7  | 82.3      | 76.2    | 84.9  |
| Vicuna   | 13B        | 86.3 | 69.4      | 92.1  | 65.4 | 83.6  | 70.4      | 83.3 | 65.2 | 69.3     | 84.2  | 72.5      | 66.2    | 75.6  |
| Phi      | 7B         | 84.9 | 67.6      | 91.0  | 63.8 | 82.6  | 68.6      | 82.1 | 63.8 | 67.6     | 82.8  | 70.8      | 64.4    | 73.8  |
| MPT      | 13B        | 86.1 | 69.2      | 92.0  | 65.2 | 83.4  | 70.2      | 83.1 | 65.0 | 69.1     | 84.0  | 72.3      | 66.0    | 75.4  |
| OPT      | 7B         | 84.7 | 67.4      | 90.8  | 63.6 | 82.4  | 68.4      | 81.9 | 63.6 | 67.4     | 82.6  | 70.6      | 64.2    | 73.6  |
Falcon
Inflection (Pi)
Grok
RoBerta
command (coher)
Starcoder
text-davinchi-003
text-bison-001
chatglm2
openchat
wizardlm
wizard coder
dolly v2
oasst sft
codex
Bert
bloom
flan t5
gpt neox
santacoder

Note: N/A means not applicable or not available. 

## The benchmarks are explained below:

- GLUE: A collection of nine natural language understanding tasks, such as sentiment analysis, textual entailment, and similarity. [1](^1^)
- SuperGLUE: A more challenging set of eight natural language understanding tasks, such as coreference resolution, natural language inference, and question answering. [2](^2^)
- SQuAD: A reading comprehension dataset consisting of questions posed by crowdworkers on a set of Wikipedia articles. [3](^3^)
- MMLU: A benchmark for measuring an LLM's knowledge across 57 STEM subjects. [4](^4^)
- GSM8K: A large set of grade-school math problems. [5](^5^)
- HumanEval: A Python coding test that requires generating code from docstrings. [6](^6^)
- MATH: A benchmark for evaluating LLMs on mathematical reasoning. [7](^7^)
- MBPP: A benchmark for evaluating LLMs on writing code based on a description. [8](^8^)
- TriviaQA: A reading comprehension dataset consisting of questions and answers obtained from trivia websites. [9](^9^)
- BoolQ: A natural language question answering dataset that requires a yes/no answer. [10](^10^)
- HellaSwag: A common sense reasoning dataset that requires choosing the most plausible ending for a given context. [11](^11^)
- AGIEval: A benchmark for evaluating LLMs on artificial general intelligence tasks, such as analogical reasoning, arithmetic, and causal reasoning. [12](^12^)

![image](https://github.com/mshojaei77/Awesome-AI/assets/76538971/41d30342-1b08-4fc8-8caf-df41d3a02841)
![image](https://github.com/mshojaei77/Awesome-AI/assets/76538971/98a1b9c8-c6a8-4b54-b1d6-b4686f045a97)
![image](https://github.com/mshojaei77/Awesome-AI/assets/76538971/5b614333-6cb6-4fb3-a3fc-2ab8c1a10357)
![image](https://github.com/mshojaei77/Awesome-AI/assets/76538971/56798ad2-5657-473b-8632-c5367451aa64)
![image](https://github.com/mshojaei77/Awesome-AI/assets/76538971/146fb9b5-977d-4f89-a9bd-48a0c479ed52)
![image](https://github.com/mshojaei77/Awesome-AI/assets/76538971/3058e91e-adce-4829-b958-faaed285d4a9)
![image](https://github.com/mshojaei77/Awesome-AI/assets/76538971/159f963b-3cf4-4ca5-9473-55c2ae1d079f)
![main_results](https://github.com/mshojaei77/Awesome-AI/assets/76538971/d5a14acb-e800-4c3e-987b-c9d3ac240dab)
![photo_2023-11-15_00-22-05](https://github.com/mshojaei77/Awesome-AI/assets/76538971/a8c719fe-a289-4574-b0bb-bda6ba0775cc)
![image](https://github.com/mshojaei77/Awesome-AI/assets/76538971/a878595f-1f17-45c8-8d95-edcdf7849c58)
![image](https://github.com/mshojaei77/Awesome-AI/assets/76538971/81bf2b47-e77b-496f-b630-ddf992c87b20)
![image](https://github.com/mshojaei77/Awesome-AI/assets/76538971/3246eba7-a966-454e-99f8-6e4de90ee586)




