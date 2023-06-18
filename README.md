# Project Title

ICI Qualifier

## Project Description

The objectives of this project are intended for users, particularly high school students who are unclear of their qualifications yet wish to apply to the Department of the International College of Innovation (ICI). The personal statements of applicants to ICI would serve as the data. The analytical methods
can help you to evaluate your strengths, experiences, and skills to determine if you are a suitable candidate or not. Our goals is to empowers the user to assess their qualification for the ICI program objectively and make informed decisions regarding their application, but the admissions committee retains the final say. It provides a structured approach to self-reflection and evaluation that might improve applicants' likelihood of making a strong application or or point out prospective areas for improvement.

## Getting Started

[Provide instructions on how to get started with your project, including any necessary software or data. Include installation instructions and any prerequisites or dependencies that are required.]

Please take the steps needed to begin using our ICI Qualifier:                                                                                                  
Firstly, click to run the code.
Secondly, copy and input your personal statement in the colum.
Thirdly, remember to click submit to see the result.
Lastly, the output would be if you're "qualified", "under consideration" or "not qualified".


## File Structure

Below is the file structure of our ICI Qualifier:

1) README.md; It contains information of our project
2) Personal_Statement.xlsx; It contains the labeled dataset which is used to generate our model.
3) ICI_qualifier.ipynb; the coding file for our ICI Qualification application.


## Analysis

[Describe your analysis methods and include any visualizations or graphics that you used to present your findings. Explain the insights that you gained from your analysis and how they relate to your research question or problem statement.]

The analytical methods of our ICI Qualifier can help you to evaluate your strengths, experiences, and skills to determine if you are a suitable candidate or not.
The Longformer model can be effectively utilized for the task of ICI personal statement qualification. As personal statements often contain long and detailed narratives that require capturing context and dependencies across the entire document. The dataset is preprocessed, cleaning it of irrelevant information and converting it into a excel file that are suitable for the Longformer model. By leveraging Longformer's ability to handle long-range dependencies in text, it becomes possible to analyze personal statements in their entirety and make accurate classification decisions. The model is then fine-tuned on the labeled training set, optimizing its performance on the task. After training, the model is evaluated using appropriate metrics to assess its accuracy and effectiveness in classifying personal statements. Evaluation on a testing set measures the model's effectiveness, and once deployed, it can classify incoming personal statements of whether they are "qualified", "under consideration", or "not qualified".

Due to the insufficient of training material that we collected or input is beyond the scope of the provided dataset, it impact our result. Therefore, this project needs continuous improvement which involves feedback collection and periodic retraining with new data to maintain high accuracy rate.

## Results

[Provide a summary of your findings and conclusions, including any recommendations or implications for future research. Be sure to explain how your results address your research question or problem statement.]

The ICI Qualifier provides a structured approach to self-reflection and evaluation that might improve applicants' likelihood of making a strong application or or point out prospective areas for improvement. User can input their personal statement and click submit so that the response will come out as "qualified", "under consideration" or "not qualified". The deployed model offers a valuable tool for decision-making in personal statement evaluation.

These findings have implications for the field of automated application screening, where AI models can assist in streamlining the process by efficiently categorizing personal statements. It is user-friendly, saves time and resources. Moreover, future research can focus on enhancing the model's performance by exploring techniques like transfer learning, ensembling, or incorporating domain-specific features.

It is essential to consider the ethical implications of using AI in decision-making processes. Transparency, fairness, and bias mitigation should be prioritized to ensure that the model's predictions are objective and unbiased. Continued feedback gathering from reviewers or applicants can help in identifying any misclassifications and improving the model's accuracy over time.

Overall, the analytic method utilizing the Longformer model provides a robust framework for personal statement qualification assessment, offering an efficient and accurate approach to assist in the decision-making process.

## Contributors

傅瑋浚 Fu Wei Chun, 王長婷 Pornnapat Pumipruek, 張嘉琳 Angeline Jia Lin Chong

## Acknowledgments

As a team, we would like to extend our heartfelt gratitude to each person who helped us with this project by offering tremendous support and assistance.

Without a doubt, we would want to express our sincere gratitude to Professor Chung-Pei Pien for kindly contributing his knowledge and experience in the area of artificial intelligence to this project. His insightful feedback and constructive suggestions significantly influenced the trajectory that this project took. He helped us significantly improve the caliber of our work. 

We also want to express our appreciation to those individuals for voluntarily allowing us access to their personal information. It was essential to get access to this data in order to undertake an in-depth analysis of our ICI Qualifier model.

Likewise, we are offer to convey our gratitude to some of our friends for their invaluable help and moral support throughout this journey. Their suggestions deepened our comprehension and raised the standard of this work as a whole.

On the final note, we want to convey our sincerity to our family for their continual support and tolerance. Their continuous support has been the driving force behind my quest for knowledge and personal development.

## References

1. Model Reference
- https://huggingface.co/spaces/freeEDU/automatic_essay_scoring-demo
2. Longformer Model
- https://huggingface.co/allenai/longformer-base-4096
3. Longformer: The Long Document Transformer
- https://arxiv.org/abs/2004.05150
