
# AI - LLM (Large Language Model) - Prompts

## Example 1
### Step and Stop - Basic - prompt

This way you give it all the context up front. This will help make responses better.
This is a prompt optimization.

**Prompt Input:**
```
Step1: 
    1. Create a socket server with node.js.

Stop and wait until I say Step2.

Step2:
    1. Create a dockerfile for the output given from Step1.

Stop and wait until I say Step3 or give Step3.
```
**Target Models:** [ChatGPT-4](https://chat.openai.com/)

## Example 2
### Step and Stop - Quiz, Grading and Results - prompt

This prompt can give a quiz to a user with all questions, gather the answers, 
then provide the grade for the full quiz and the results.

**Prompt Input:**
```
Quiz User: After each 'Question', Stop and wait for the users response to each question. 
At the end of all questions and the users responses, 
then provide a grade and results of the entire Quiz.

Question1: What is 1+1=?
Question2: What does 2*2=?
```
**Target Models:** [ChatGPT-4](https://chat.openai.com/)

## License

This project is licensed under the [MIT License](LICENSE).