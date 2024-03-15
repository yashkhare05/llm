# LLM

LLAMA model is the open weight biggest LLM( we can see the model architecture)

LLAMA 2-70b has 2 files 
1. parameters - 140GB size
2. run.c - to implement params ( no external dependencies to implement the Neural network) can take .py as well

What is in the parameters?
We have huge chunk of internet and run on high GPU's and compress into params(lossy compression)
![image](https://github.com/yashkhare05/llm/assets/158818094/52386a7d-3876-4dd5-bea3-27da012ca8d8)

The main objective of LLM is to guess next words and learn after every steps. Though not as same as training dataset but can take huge references and makes it in correct form
![image](https://github.com/yashkhare05/llm/assets/158818094/78d7b487-b628-49e5-9b39-6ad91a8c098e)

Training the assistant with q&a documents (finetuning the LLM) . we get a system model which subscribe to the data. It infers that it should behave to assistant type. 
We ask people to make questions and answer them and then LLM is trained upon them
![image](https://github.com/yashkhare05/llm/assets/158818094/73a15988-d6f7-4e6f-a284-a52f9cadb74f)

Performance of LLM is focused on 2 parameters
1. NUmber of parameters in the network
2. the amount of text we train on
