# TEXT-SUMMARIZATION-TOOL
COMPANY : CODTECH IT SOLUTIONS

NAME : BATHALA HIMASREE

INTERN ID :CT06DG1957

DOMAIN : ARTIFICIAL INTELLIGENCE

DURATION : 6 WEEKS

MENTOR : NEELA SANTOSH


In Task 1 of the internship, I developed a Text Summarization Tool using Natural Language Processing (NLP) techniques. The objective was to take a long paragraph and reduce it to a short, meaningful summary while preserving the core message. This task was performed in Jupyter Notebook, using the Python kernel and the Transformers library by Hugging Face.

Text summarization is a crucial NLP task that simplifies large text bodies into brief, informative summaries. I implemented this using the pipeline() API from the Transformers library, which allows the use of pre-trained models with minimal setup. I specifically used the summarization pipeline with the DistilBART model: sshleifer/distilbart-cnn-12-6, which is fine-tuned for summarizing English text such as news articles.

After importing the required modules, I loaded the summarizer pipeline and provided a long text paragraph as input. The model used attention mechanisms and its encoder-decoder architecture to identify and retain the most important sentences. The result was printed as a concise and coherent summary. This process involved no manual training or dataset preparation, thanks to the availability of pre-trained models.

The summarization pipeline automatically handles tokenization, encoding, decoding, and sentence structuring. I learned how sequence-to-sequence models work under the hood, especially the importance of transformer-based architectures in solving language understanding tasks. These models are trained on massive corpora and are capable of capturing the context and semantic importance of words in a paragraph.

Real-world applications of text summarization are vast. In news aggregation platforms, summarization helps users get the gist of multiple articles quickly. In education, it assists students in creating concise study notes from lengthy materials. In legal and medical fields, large documents and case studies can be summarized for fast decision-making. Customer support systems use summarization to create ticket summaries or summarize long email threads. Social media analytics platforms also rely on summarization for extracting key insights from long user-generated content.

The tools used in this task included:

Jupyter Notebook for execution

Python for scripting

Transformers by Hugging Face for the model

PyTorch backend for running the model inference

This task helped me understand the importance of summarization in modern AI-powered workflows. It gave me practical experience in integrating pre-trained models, interpreting results, and understanding NLP from a functional point of view. It also introduced me to challenges like input token limits, text length constraints, and model output formatting.

In conclusion, Task 1 allowed me to build a fully functional text summarization tool with real-world utility. It provided an excellent introduction to Hugging Face Transformers and showed me how transformer models like BART can be used for powerful NLP solutions. This experience formed a strong foundation for the remaining tasks in the internship.

**OUTPUT:
<img width="1635" height="152" alt="Image" src="https://github.com/user-attachments/assets/54c9a16b-d912-4f0a-97d9-884fd836650f" />
