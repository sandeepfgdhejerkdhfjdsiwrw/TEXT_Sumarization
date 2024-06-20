# TEXT_Sumarization
Text summarization of long documents   using Transformers 
The proposed method utilizes a transformer-based Seq2Seq model for summarizing long documents. Specifically, it employs the "sshleifer/distilbart-cnn-12-6" checkpoint, which is a distilled version of BART optimized for summarization tasks. The approach involves tokenizing the input text, handling long documents by splitting them into manageable chunks, generating summaries for each chunk, and combining these summaries into a coherent final summary.

Steps Involved:
1)Model Initialization: Load the pre-trained tokenizer and model from the specified checkpoint.

2)Preprocessing the Input: Tokenize the input text and handle long documents by splitting them into manageable chunks.

3)Summarization: Generate summaries for each chunk using the Seq2Seq model.

4)Postprocessing: Combine the generated summaries into a single coherent summary.

This approach ensures that the model can handle long texts and produce high-quality summaries efficiently, addressing the challenges of scalability, coherence, and content diversity. By leveraging the strengths of transformer-based models, our method aims to provide a robust solution for automated text summarization across various domains.
