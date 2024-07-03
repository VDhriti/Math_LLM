# Improving Math Reasoning for College Level Math

**Idea:** Have 3 models debate on the solution to a problem. 
- Have the first LLM generate 2 approaches to solve the problem with confidence levels in its approach [1] (use math specialized model)
- Have the second model critique both methods, and first LLM correct itself/ defend itself (use a model that is good with proofs and theorems) [1]
- Have the final model 1. Evaluate the best method from the debate given the original problem and solve it. 2. Generate python code to solve the problem. (Maybe use an unbiased analyser that can be a weak model [2] + coding model)


**Goal:** To do well on college level math. Introduction Analysis, Linalg

**Testing Datatsets:**
1. GSM8K
2. College Math Textbook Exercises

## References

1. Improving Factuality and Reasoning in Language Models through Multiagent Debate https://arxiv.org/pdf/2305.14325 

2. Debating with More Persuasive LLMs Leads to More Truthful Answers (https://arxiv.org/html/2402.06782v2) 
