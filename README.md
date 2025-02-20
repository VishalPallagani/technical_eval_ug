# Technical Evaluation - Undergraduate

## Instructions
Fork this repository, answer both technical and coding questions in a Jupyter notebook, and upload it to your forked repository. Share your GitHub repository with answers for evaluation.

## **Technical Questions**
### **PyTorch**
1. What is the difference between `torch.Tensor` and `torch.autograd.Variable`? When should you use `Variable` in PyTorch?
2. Explain the role of `torch.nn.Module` and why it is commonly used in PyTorch models.
3. How do you perform backpropagation in PyTorch, and why is `torch.no_grad()` useful?
4. Compare the use of `torch.optim.Adam` and `torch.optim.SGD`. When should each be used?
5. What is a computational graph in PyTorch, and how does it facilitate automatic differentiation?

### **Hugging Face and Transformers**
1. What are the key components of the `transformers` library from Hugging Face?
2. How does `AutoModel` differ from `AutoModelForSequenceClassification`?
3. What is a tokenizer, and why is it necessary when working with transformer models?
4. How do you fine-tune a Hugging Face transformer model on a custom dataset?
5. Explain the difference between `Trainer` and manually implementing a training loop using PyTorch.

## **Coding Exercise: Predicting Hit Songs**
### **Goal**
Spotify is one of the most popular streaming platforms, and its API provides access to detailed audio and descriptive features for songs. The primary goal of this exercise is to define a relationship between these features and the likelihood of a song becoming a hit.

### **Mathematical Representation**
```
Hit Song → f(A, D)
# A represents the audio features of a song
# D represents the descriptive features of a song
```

### **Research Questions**
1. What features most significantly influence the likelihood of a song becoming a hit, and do these features vary across genres?
2. How does the release date (e.g., month, season) impact a song’s popularity, and are certain time frames consistently better for specific genres?
3. What values of audio features can consistently create a hit song, and how do these values differ across genres?

### **Tasks**
1. **Perform Exploratory Data Analysis (EDA):**
   - Summarize the dataset, check for missing values, and handle them appropriately.
   - Visualize the distribution of key features.
   - Analyze correlations between features and track popularity.

2. **Build a Predictive Model:**
   - Train a model using to predict song popularity.
   - Use appropriate evaluation metrics such as accuracy, RMSE, or F1-score.

3. **Visualization & Explanation:**
   - Use visualizations to support the research questions.
   - Explain your approach, challenges faced, and insights gained from the analysis.

## **Submission Guidelines**
- Your Jupyter notebook should be well-documented with explanations and visualizations.
- Ensure that your code is modular and reusable.
- Push the completed notebook to your forked repository and share the link for evaluation.

Good luck!

