# Prompt Engineering: In-context learning with GPT-3 and other Large Language Models 
## objective 
- Entity Extraction
- Document Score
## Entity Extraction
Extracting a piece of information from text is a common need in language processing systems. LLMs can extract entities which are harder to extract using other NLP methods (and where pre-training provides the model with some context on these entities). This is an overview of using generative LLMs to extract entities.
<p> <image src = "llm.PNG" alt = "llm"/> </p>

## Document Score
Given a news item as json with title, description, and body of the content, return a score between 0 and 10 in one or two significant digits e.g. (1.2 or 0.33).
- classification of the news dataset into class based on average score
