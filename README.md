This project explores ChatGPT’s intelligence through a neuropsychological evaluation and investigates its lie detection capabilities using stylometric analysis. The study assesses ChatGPT’s cognitive abilities through prefrontal functioning tests and compares its recall capabilities to the human brain. Additionally, it evaluates ChatGPT-2 for detecting deception in textual data.

* Key Components
  

Dataset Used: The Memory Dataset containing truthful and deceptive narratives.

Fine-tuning Approach: ChatGPT-2 was fine-tuned on a portion of the dataset and tested on unseen data.

Text Processing: Preprocessing included removing null and short stories, tokenization using GPT-2, and classification with GPT-2 ForSequenceClassification.

Performance Comparison:

ChatGPT-2 achieved 89% accuracy in detecting deception. Outperformed BART (79%) and FLAN-T5 (80.6%).

Stylometry analysis highlighted linguistic differences between truthful and deceptive statements.

* Key Findings
  
ChatGPT demonstrates human-like cognitive abilities in language tasks, but does not fully replicate human reasoning in prefrontal tests.

ChatGPT-2 shows high accuracy in lie detection, suggesting potential applications in forensic linguistics.

Fine-tuned LLMs outperform other NLP models in deception detection, indicating their adaptability for specialized tasks.
