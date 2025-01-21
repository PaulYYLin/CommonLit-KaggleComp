# CommonLit-KaggleComp
20230923

NLP Task
Using TensorFlow 2.0 as model building framework

### Segments
#### Text Preprocessing
Remove stopwords (NLTK, english) --> Stem --> Tokenize --> Padding --> Vectorized

<img width="905" alt="image" src="https://github.com/user-attachments/assets/8cb085fc-13d3-468f-a3f5-c5694d366e3f" />


#### Model

1. Model Build (TF)

2. Hyperparameters Optimization (Optuna)
{'output_dim': 48,
 'LSTM_units': 8,
 'FC_output': 12,
 'FC1_activation': 'LeakyReLu',
 'batch_size': 32}
 
3. Model Training --> Training Visualization

   <img width="522" alt="image" src="https://github.com/user-attachments/assets/e0e0fe31-c828-4882-b822-2d1f2c976cdd" />
   
  ![image](https://github.com/user-attachments/assets/0886d358-d37f-4a1a-b3eb-81efc9327769)

4. content >>> wording score

