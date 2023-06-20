# Project Title

ICI Qualifier

## Project Description

The objectives of this project are intended for users, particularly high school students who are unclear of their qualifications yet wish to apply to the Department of the International College of Innovation (ICI). The personal statements of applicants to ICI would serve as the data. The analytical methods
can help you to evaluate your strengths, experiences, and skills to determine if you are a suitable candidate or not. Our goal is to empower the user to assess their qualification for the ICI program objectively and make informed decisions regarding their application, but the admissions committee retains the final say. It provides a structured approach to self-reflection and evaluation that might improve applicants' likelihood of making a strong application or point out prospective areas for improvement.

## Getting Started

Please take the steps needed to begin using our ICI Qualifier:                                                                                                  
Firstly, click to run the code.
Secondly, copy and input your personal statement in the column.
Thirdly, remember to click submit to see the result.
Lastly, the output would be if you're "qualified", "under consideration" or "not qualified".


## File Structure

Below is the file structure of our ICI Qualifier:

1) README.md; It contains information about our project
2) Personal_Statement.xlsx; It contains the labeled dataset which is used to generate our model.
3) ICI_qualifier.ipynb; the coding file for our ICI Qualification application.


## Analysis

[Describe your analysis methods and include any visualizations or graphics that you used to present your findings. Explain the insights that you gained from your analysis and how they relate to your research question or problem statement.]

Our ICI Qualifier's method of analysis can assist you in evaluating your expertise, experiences, and skills to determine whether you are an appealing prospect or not. The Longformer model can be used successfully for the ICI personal statement task. Given that personal statements frequently contain extensive and comprehensive narratives, it is necessary to capture context and dependencies throughout the document. The dataset is preprocessed, with unnecessary information removed and converted into an Excel file suitable for the Longformer model. It is now able to assess personal statements in their entirety and make proper classification decisions by utilizing Longformer's capacity to handle long-term dependencies in text. The model is then fine-tuned on the labeled training set to optimize its task performance. The model is assessed after training using relevant metrics to determine its accuracy and effectiveness in classifying personal statements. The model's effectiveness is measured on an assessment set, and once implemented, it may classify incoming personal statements as "qualified," "under consideration," or "not qualified." 

We run into two limitations: insufficient training material or input that is outside the scope of the available dataset, both of which have an impact on our results. To maintain a high accuracy rate, this project requires continual development, which includes feedback collecting and occasional retraining with new data.

## Results

The ICI Qualifier offers a methodical framework for evaluation and self-reflection that may increase applicants' chances of submitting compelling applications or identifying potential areas for growth. The user may paste their personal statement and click submit to get a response of "qualified", "under consideration", or "not qualified". The model used serves as a useful decision-making tool in the evaluation of personal statements.

These findings have significance for the field of automated application screening, where AI models can help to streamline the process by categorizing personal statements efficiently. It is simple to use and saves time and resources. Furthermore, future research can concentrate on improving the model's performance by experimenting with tactics such as transfer learning, ensembling, or integrating domain-specific features.

The ethical consequences of deploying AI in decision-making processes must be considered. To ensure that the model's predictions are impartial and unbiased, transparency, fairness, and bias avoidance should be prioritized. Continuous feedback from reviewers or applicants can aid in the identification of misclassifications and enhance the model's accuracy over time.

Overall, the Longformer model-based analytic method provides a solid foundation for personal statement qualification assessment, providing an efficient and accurate approach to aid in decision-making.

## Contributors

傅瑋浚 Fu Wei Chun, 王長婷 Pornnapat Pumipruek, 張嘉琳 Angeline Jia Lin Chong

## Acknowledgments

As a team, we would like to extend our heartfelt gratitude to each person who helped us with this project by offering tremendous support and assistance.

Without a doubt, we would want to express our sincere gratitude to Professor Chung-Pei Pien for kindly contributing his knowledge and experience in the area of artificial intelligence to this project. His insightful feedback and constructive suggestions significantly influenced the trajectory that this project took. He helped us significantly improve the caliber of our work. 

We also want to express our appreciation to those individuals for voluntarily allowing us access to their personal information. It was essential to get access to this data in order to undertake an in-depth analysis of our ICI Qualifier model.

On the final note, we want to convey our sincerity to our family for their continual support and tolerance. Their continuous support has been the driving force behind my quest for knowledge and personal development.

## References

1. Model Reference
- https://huggingface.co/spaces/freeEDU/automatic_essay_scoring-demo
2. Longformer Model
- https://huggingface.co/allenai/longformer-base-4096
3. Longformer: The Long Document Transformer
- https://arxiv.org/abs/2004.05150
