# Title  
Lucid Tokens: Visual Insights into How LLMs Process Text  
  
# Abstract  
  
Large Language Models (LLMs) break down a text prompt into small fragments (called tokens) to understand and generate language.   
In this session, I want to take a deep dive into the fundamental process of tokenization and subword splitting — crucial techniques that enable LLMs to handle diverse vocabularies efficiently.  
Through clear visualizations and easy to replicate notebooks, you will gain a deep understanding of how text is broken down before it enters a language model and how this affects model performance.   
By the end of this talk, you will be equipped with insights that you can apply to enhance your own AI / GenAI projects.  
    
All code and presentation materials will be openly available on GitHub: https://github.com/shauryashaurya/Deep-Learning-Labs/tree/main/Tokenization-ideas-for-LLMs  
# Description  
  
Tokenization is the key first step in how transformers based Large Language Models process text based input queries (or prompts). 
In this talk I want to get into the inner workings of tokenization and subword splitting — core techniques that allow LLMs to handle vast and diverse vocabularies efficiently.

Using intuitive visualizations, we examine how sentences are broken down into tokens and subwords, highlighting why these choices significantly impact model performance, efficiency, and ability to generalize. 
I want to visualize how different tokenization methods like Byte Pair Encoding (BPE) split the text, and compare the results of various prompts/queries.

The talk leverages Python and Hugging Face's tokenizers, providing an easy-to-replicate notebook, so you can refer to it later and hopefully also build upon these techniques after the session.   
By understanding the tokenization process, you will be equipped with better insights into tasks such as text generation, and more.  

All code and presentation materials will be openly available on GitHub: https://github.com/shauryashaurya/Deep-Learning-Labs/tree/main/Tokenization-ideas-for-LLMs  
  
Possible Session Outline (30-ish minutes)(developing further as of this proposal):  
  
* Introduction to Tokenization in LLMs (5 minutes)  
   - Overview of tokenization and its role in language processing.  
   - Importance of subword splitting in handling diverse vocabularies.  
* Visualizing Tokenization Processes (15 minutes)  
   - Demonstration of how sentences are broken down into tokens and subwords.  
   - Visual examples highlighting differences between full-word tokenization and subword methods like BPE.  
* Impact of Tokenization on Model Performance (5 minutes)  
   - Discuss how tokenization choices affect LLM performance, efficiency, and generalization.  
   - Tips on selecting appropriate tokenization strategies for your projects.  
   
Takeaways:

- Tokenize text using various methods and visualize the results  
- Insights into how tokenization affects language model behavior and performance  
  
# Notes
Target Audience: suitable for data scientists - novice or practicing, AI/ML engineers, and GenAI/NLP practitioners at all levels who may be interested in building modern recommendation systems. Basic knowledge of Python and familiarity with LLMs or NLP concepts is recommended, but not required.   