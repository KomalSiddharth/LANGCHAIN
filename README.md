# LANGCHAIN_ERROR
This is repository is all about what all errors i faced when i started working with llm models throughtout my learning journey.

Well I'm a beginner who have just dived into the vast ocean of knowledge related to various new Technologies.
Hustling everyday to learn something new.
So I have recently started exploring Langchain models which are in huge trend these days becoz of its improvised predicting capablity and many more functionalities.

# What is LLM chains?
=> The LLM models are mainly created to get more accurate and precise results from the models we train. Here we set term "Temperature" which defines how our model would be predicting the outputs based on the inputs provided.If the value of temperature is 1 or nearer then the model is going to predict variable or in order words we can say more accurate results but if the values is around 0 then it predicts almost same type of answers.
LLMChains are a powerful technique for enhancing the capabilities of language models. Instead of relying on a single LLM completion, chains employ multiple completions followed by actions in a sequential manner to generate more accurate and contextually appropriate responses. You can think of it as a multi-step approach to solving a problem.
It consists of two main parts: Prompt_template and llm models


Well when i was working on my llm models,i got across an error named "ratelimit error" though i tried to understand what does it means and figured it out as well but still stuck with how can i get rid from it in order to get the output.
here's the error what i m  getting,
RateLimitError: Error code: 429 - {'error': {'message': 'You exceeded your current quota, please check your plan and billing details. For more information on this error, read the docs: https://platform.openai.com/docs/guides/error-codes/api-errors.', 'type': 'insufficient_quota', 'param': None, 'code': 'insufficient_quota'}}
Output is truncated. View as a scrollable element or open in a text editor. Adjust cell output settings...

well finally i got the solution,these ratelimit error occurs just becoz of the token limit provided by the clous services.So if these error arises then u can simply buy credit points to acceess the services provided by openAI or else if u dont want to invest any amount then u can simply create another account and u can simply get 5$ credits so that u can temporily access OpenAI services.
