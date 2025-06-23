Generative AI has rapidly transformed how we interact with technology, from crafting compelling stories to designing stunning visuals. To navigate this exciting landscape, a solid grasp of the terminology is essential. This glossary provides an overview of key terms, demystifying the complex world of generative AI. Let's dive in!


## A glossary of generative AI terminology:

- Generative AI: AI systems capable of creating new content, such as text, images, or audio.
*LLM:* Often referred to as "AI models", a "Large Language Model" is trained on vast amounts of text data, its purpose is to understand and generate human-like text.
- Hallucination: 
When an LLM generates plausible but factually incorrect or nonsensical information.
- Inference: The process of using a trained model to make next token predictions or "generate" output.
- Tokenization: The process of breaking text into smaller units (tokens) that the model can process.
- Token: A token can be a word, punctuation mark, or even a sub-word unit.
- Special Token: These are reserved tokens intended for a function of the LLM. For example <|start|> or <|end|> would determine when the model would start or end something like a reply or a users message. Each model has its own special tokens that must be used appropriately or the model will not behave as expected.
- Prompt template: 
Specially formatted instructions used by the LLM to define the information passed to and from it. These require "Special Tokens" to function properly.
- System prompts: Instructions or context given to an LLM to define its behavior, personality, or role in a conversation. These require "Special Tokens" to function properly, and the model should also be designed to expect a system prompt.
- Prompt engineering: The art of crafting effective inputs to elicit desired output from an LLM.
- Zero-shot: The ability of a model to perform tasks it wasn't explicitly trained on, based on its general knowledge.
Few-shot: Using a small number of examples to guide the model in performing a new task.
Perplexity: A measure of how well a language model predicts a sample of text, often used to evaluate model performance. A lower score is better.
- Training: This involves feeding the model massive amounts of text data and allowing it to learn patterns and relationships between words.
- Base model: The original, foundational version of a large language model. This model has not been "fine-tuned".
- Pre-trained model: An interchangeable term for a model which may be either a base model or one modified from the base dataset.
- Fine-tuning: Adapting a pre-trained model to a specific task or domain by training it on a smaller, specialized dataset.
- LoRA: Low-Rank Adaptation, a variant of Fine-tuning which requires less computational resources compared to full fine-tuning.
- Dataset: The training data used to teach an LLM patterns and information during its training phase.
- R.A.G. (Retrieval-Augmented Generation): A technique that combines information retrieval from external sources with the generative capabilities of an LLM to produce more accurate and up-to-date responses.
Embeddings: You can imagine Embeddings are like digital maps of words or phrases. They turn text into lists of numbers (vectors) that computers can easily work with.
