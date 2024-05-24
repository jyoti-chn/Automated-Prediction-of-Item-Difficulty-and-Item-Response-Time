# Automated-Prediction-of-Item-Difficulty-and-Item-Response-Time
A regression model to accurately predict item difficulty and response time based on item text for standardized exams to be fair and valid

## Dataset
- **Source:** Practice item content from the United States Medical Licensing Examination (USMLE)
- **Samples:** 466
- **Variables:** 18
- **Types of Questions:** multiple-choice questions (MCQs) from USMLE Steps 1, 2CK, and 3


3. **Feature Engineering:**
   - Integrated Flesch Readability score to capture linguistic information.
   - Incorporated contextual embeddings from BERT to leverage both syntactic and semantic information.
4. **Model Development:**
   - Built a regression model with combined feature vectors including `ques_type`, `exam_type`, `ques_text`, `combined_answer_text`, `Answer_Text`, and `Flesch Readability Score`.
   - Predicted text difficulty level and response time using these combined features.
5. **Regularization:**
   - Implemented L2 regularization techniques to enhance the accuracy and generalization capability of the models.
6. **Evaluation:**
   - Assessed model performance using Root Mean Square Error (RMSE).


## Tools and Technologies
- **Programming Language:** Python
- **Libraries:** Pandas, Scikit-learn, TensorFlow, BERT, Matplotlib, Seaborn

