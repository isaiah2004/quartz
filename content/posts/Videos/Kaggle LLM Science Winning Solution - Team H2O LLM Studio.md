# Kaggle LLM Science Winning Solution - Team H2O LLM Studio

Video link:
[(93) Kaggle LLM Science Winning Solution | Team H2O LLM Studio - YouTube](https://www.youtube.com/watch?v=fViGQqv2xfc)

Kaggle submission :
[Kaggle - LLM Science Exam | Kaggle](https://www.kaggle.com/competitions/kaggle-llm-science-exam/discussion/446422)

### AI [[Notes]] 
**Summary of the video in bullets and sections:**

- **Introduction**
    - This video summarizes the winning solution from the Kaggle LLM Science Competition by team H2O LLM Studio.
    - The speaker will explain the problem statement, the team's solution, and the validation approach.
- **Problem Statement**
    - The competition challenged participants to train a large language model (LLM) to answer multiple-choice questions (MCQs) based on a dataset of open ended questions.
    - The difficulty was that the organizers did not provide any training data.
- **Team H2O LLM Studio's Solution**
    - The team's solution involved using Retrieval-Augmented Generation (RAG) and fine-tuning six LLMs.
    - RAG involves retrieving relevant passages from a large dataset (Wikipedia in this case) to answer the question in context.
    - The six LLMs were fine-tuned on a dataset created from the retrieved passages and the MCQs.
    - The final answer was chosen by averaging the probabilities from the six LLMs for each option.
- **Key Points**
    - The team used a massive dataset of Wikipedia entries (around 1.5 terabytes).
    - They implemented a similarity search to efficiently retrieve relevant passages from the Wikipedia data.
    - They used a combination of different embedding models and retrieval LLM models.
    - They fine-tuned the LLMs on a dataset converted into a binary classification problem.
    - They used LLM Studio for fine-tuning the models and adding a dense layer for classification.
- **Conclusion**
    - Team H2O LLM Studio's solution achieved first place in the competition.
    - The speaker encourages viewers to check out the team's write-up and video for more details.


#ai #GenAi #llms #Kaggle #Project