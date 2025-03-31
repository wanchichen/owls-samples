
Caption: The ICL embedding mining process for selecting _k_ in-context examples. For a single test audio input, the encoder extracts an audio embedding of the test audio _and_ all audio samples in the ICL training set. The embeddings are averaged across the sequence dimension. The in-context examples are selected by choosing the top _k_ embeddings with the smallest L2 distance from the test audio embedding.
![image](https://github.com/user-attachments/assets/f7550df3-9736-4596-a5e6-a36c929d2bfa)

Caption: The ICL inference process. The in-context examples are obtained from the above figure. The speech of the in-context examples and test audio are concatenated along the sequence dimension. The text of the in-context examples are also concatenated and used as a prompt for the decoder.
![image](https://github.com/user-attachments/assets/d6292d06-636f-4b20-b2b9-0764197d5f01)
